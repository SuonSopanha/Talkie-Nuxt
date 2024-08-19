<template>
    <div class="flex flex-wrap justify-center mx-6">
        <!-- Sidebar -->
        <div class="w-full md:w-1/4 p-4 border-r border-gray-300 flex flex-col space-y-3">
            <SidebarMenu />
        </div>

        <!-- Main Content: Create Post Form -->
        <div class="w-full md:w-1/2 bg-white p-4">
            <h2 class="text-xl font-bold mb-6">Create a Community</h2>

            <!-- Create Community Form -->
            <form @submit.prevent="handleSubmit" class="space-y-6">
                <!-- Step 1: Community Name and Description -->
                <div v-if="step === 1">
                    <div>
                        <label for="community-name" class="block text-sm font-medium text-gray-700">Community
                            Name</label>
                        <input type="text" id="community-name" v-model="form.communityName"
                            class="mt-1 block w-full border border-gray-300 rounded-md p-2 shadow-sm focus:ring-teal-500 focus:border-teal-500 sm:text-sm"
                            placeholder="e.g., myawesomecommunity">
                        <p class="mt-2 text-sm text-gray-500">Community names including capitalization cannot be
                            changed.</p>
                    </div>
                    <div>
                        <label for="community-description"
                            class="block text-sm font-medium text-gray-700">Description</label>
                        <textarea id="community-description" v-model="form.communityDescription" rows="3"
                            class="mt-1 block w-full border border-gray-300 rounded-md p-2 shadow-sm focus:ring-teal-500 focus:border-teal-500 sm:text-sm"
                            placeholder="Describe your community"></textarea>
                        <p class="mt-2 text-sm text-gray-500">This is how new members come to understand your community.
                        </p>
                    </div>
                </div>

                <!-- Step 2: Icon and Banner -->
                <div v-if="step === 2">
                    <div>
                        <label for="community-icon" class="block text-sm font-medium text-gray-700">Community
                            Icon</label>
                        <input type="file" id="community-icon" @change="handleIconUpload"
                            class="mt-1 block w-full text-sm text-gray-900 border border-gray-300 rounded-md cursor-pointer focus:outline-none">
                        <p class="mt-2 text-sm text-gray-500">Choose an icon for your community.</p>
                    </div>
                    <div>
                        <label for="community-banner" class="block text-sm font-medium text-gray-700">Community
                            Banner</label>
                        <input type="file" id="community-banner" @change="handleBannerUpload"
                            class="mt-1 block w-full text-sm text-gray-900 border border-gray-300 rounded-md cursor-pointer focus:outline-none">
                        <p class="mt-2 text-sm text-gray-500">Choose a banner image for your community.</p>
                    </div>
                </div>

                <!-- Step 3: Topic -->
                <div v-if="step === 3">
                    <div>
                        <label for="community-topic" class="block text-sm font-medium text-gray-700">Topic</label>
                        <input type="text" id="community-topic" v-model="form.communityTopic"
                            class="mt-1 block w-full border border-gray-300 rounded-md p-2 shadow-sm focus:ring-teal-500 focus:border-teal-500 sm:text-sm"
                            placeholder="e.g., Technology, Art, etc.">
                        <p class="mt-2 text-sm text-gray-500">What is your community about?</p>
                    </div>
                </div>

                <!-- Step 4: Settings -->
                <div v-if="step === 4">
                    <div>
                        <label for="community-type" class="block text-sm font-medium text-gray-700">Community
                            Type</label>
                        <select id="community-type" v-model="form.communityType"
                            class="mt-1 block w-full border border-gray-300 rounded-md p-2 shadow-sm focus:ring-teal-500 focus:border-teal-500 sm:text-sm">
                            <option>Public</option>
                            <option>Restricted</option>
                            <option>Private</option>
                        </select>
                        <p class="mt-2 text-sm text-gray-500">Who can view and join your community.</p>
                    </div>
                </div>

                <!-- Step 5: Rules -->
                <div v-if="step === 5">
                    <div>
                        <label for="community-rules" class="block text-sm font-medium text-gray-700">Community
                            Rules</label>
                        <textarea id="community-rules" v-model="form.communityRules" rows="3"
                            class="mt-1 block w-full border border-gray-300 rounded-md p-2 shadow-sm focus:ring-teal-500 focus:border-teal-500 sm:text-sm"
                            placeholder="State the rules of your community"></textarea>
                        <p class="mt-2 text-sm text-gray-500">Help members understand the do's and don'ts.</p>
                    </div>
                </div>

                <!-- Navigation Buttons -->
                <div class="flex justify-between">
                    <button type="button" v-if="step > 1" @click="prevStep"
                        class="bg-gray-300 text-gray-700 font-bold py-2 px-4 rounded-lg">
                        Previous
                    </button>
                    <button type="button" v-if="step < 5" @click="nextStep"
                        class="bg-teal-600 text-white font-bold py-2 px-4 rounded-lg">
                        Next
                    </button>
                    <button type="submit" v-if="step === 5"
                        class="bg-teal-600 text-white font-bold py-2 px-4 rounded-lg">
                        Create Community
                    </button>
                </div>
            </form>
        </div>

        <!-- Sidebar: Join Community and Related Posts -->
        <div class="w-full md:w-1/4 bg-gray-100 p-4 border-l border-gray-300">
            <div class="sticky top-0">
                <!-- Join Community Section -->
                <div class="relative isolate overflow-hidden text-center rounded-lg p-4">
                    <h2 class="font-bold text-xl uppercase tracking-wide sm:text-2xl">Join our community now</h2>
                    <p class="mt-4 text-sm leading-6 text-gray-600">
                        Experience the benefits of our community. No obligations, just join and explore.
                    </p>
                    <div class="isolate mt-4 flex items-center justify-center -space-x-2 overflow-hidden">
                        <img class="relative z-30 inline-block h-8 w-8 rounded-full ring-2 ring-white"
                            src="https://randomuser.me/api/portraits/men/34.jpg" alt="">
                        <img class="relative z-20 inline-block h-8 w-8 rounded-full ring-2 ring-white"
                            src="https://randomuser.me/api/portraits/women/2.jpg" alt="">
                        <img class="relative z-10 inline-block h-8 w-8 rounded-full ring-2 ring-white"
                            src="https://randomuser.me/api/portraits/women/3.jpg" alt="">
                        <img class="relative z-0 inline-block h-8 w-8 rounded-full ring-2 ring-white"
                            src="https://randomuser.me/api/portraits/men/4.jpg" alt="">
                        <span class="ml-2 font-bold italic text-teal-500">Join these awesome members</span>
                    </div>
                    <div class="mt-6 flex items-center justify-center">
                        <button type="button"
                            class="text-sm inline-flex items-center gap-x-2 rounded-lg bg-teal-600 px-4 py-2 font-semibold text-white shadow-sm hover:bg-teal-500">
                            Join Now
                        </button>
                    </div>
                </div>

                <!-- Related Posts -->
                <div class="bg-white border border-gray-200 rounded-lg shadow-sm p-4 mt-6">
                    <h2 class="text-lg font-semibold text-gray-900 mb-4">Related Posts</h2>

                    <!-- Add related post components here (same as your previous layout) -->

                </div>
            </div>
        </div>
    </div>
</template>


<script>
export default {
    data() {
        return {
            step: 1,  // Start at step 1
            form: {
                communityName: '',
                communityDescription: '',
                communityIcon: null,
                communityBanner: null,
                communityTopic: '',
                communityType: 'Public',
                communityRules: ''
            }
        };
    },
    methods: {
        nextStep() {
            if (this.step < 5) {
                this.step++;
            }
        },
        prevStep() {
            if (this.step > 1) {
                this.step--;
            }
        },
        handleIconUpload(event) {
            this.form.communityIcon = event.target.files[0];
        },
        handleBannerUpload(event) {
            this.form.communityBanner = event.target.files[0];
        },
        handleSubmit() {
            // Handle form submission (e.g., send data to API)
            console.log(this.form);
            alert("Community Created!");
        }
    }
};
</script>