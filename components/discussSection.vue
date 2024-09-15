<template>
    <div class="mt-6">
        <h2 class="text-lg font-semibold text-gray-900 mb-4">Comments</h2>

        <!-- Comment -->
        <div class="flex items-start space-x-4 mb-4">
            <img src="https://randomuser.me/api/portraits/men/32.jpg" alt="User Avatar"
                class="w-10 h-10 rounded-full object-cover">
            <div class="flex-1">
                <p class="font-medium text-gray-900">u/Commenter1</p>
                <p class="text-gray-700 text-sm">
                    This guide is amazing! I learned so much about Tailwind CSS. Thanks for sharing!
                </p>
                <div class="flex items-center space-x-2 mt-2">
                    <button class="text-gray-500 hover:text-blue-600 focus:outline-none items-center mt-1">
                        <Icon name="material-symbols:arrow-circle-up-outline" size="20"></Icon>
                    </button>
                    <span class="text-md text-gray-700">12</span>
                    <button class="text-gray-500 hover:text-red-600 focus:outline-none items-center mt-1">
                        <Icon name="material-symbols:arrow-circle-down-outline" size="20"></Icon>
                    </button>
                </div>
                <!-- Nested Comment -->
                <div class="flex items-start space-x-4 mt-4">
                    <img src="https://randomuser.me/api/portraits/men/45.jpg" alt="User Avatar"
                        class="w-8 h-8 rounded-full object-cover">
                    <div class="flex-1">
                        <p class="font-medium text-gray-900">u/NestedCommenter1</p>
                        <p class="text-gray-700 text-sm">
                            Totally agree! This guide is super helpful.
                        </p>
                        <div class="flex items-center space-x-2 mt-2">
                            <button class="text-gray-500 hover:text-blue-600 focus:outline-none items-center mt-1">
                                <Icon name="material-symbols:arrow-circle-up-outline" size="20"></Icon>
                            </button>
                            <span class="text-md text-gray-700">12</span>
                            <button class="text-gray-500 hover:text-red-600 focus:outline-none items-center mt-1">
                                <Icon name="material-symbols:arrow-circle-down-outline" size="20"></Icon>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Comment -->
        <div class="flex items-start space-x-4">
            <img src="https://randomuser.me/api/portraits/women/44.jpg" alt="User Avatar"
                class="w-10 h-10 rounded-full object-cover">
            <div class="flex-1">
                <p class="font-medium text-gray-900">u/Commenter2</p>
                <p class="text-gray-700 text-sm">
                    I've been using Tailwind for a while, and this guide is a great resource for beginners.
                </p>
                <div class="flex items-center space-x-2 mt-2">
                    <button class="text-gray-500 hover:text-blue-600 focus:outline-none items-center mt-1">
                        <Icon name="material-symbols:arrow-circle-up-outline" size="20"></Icon>
                    </button>
                    <span class="text-md text-gray-700">12</span>
                    <button class="text-gray-500 hover:text-red-600 focus:outline-none items-center mt-1">
                        <Icon name="material-symbols:arrow-circle-down-outline" size="20"></Icon>
                    </button>
                </div>
                <!-- Nested Comment -->
                <div class="flex items-start space-x-4 mt-4">
                    <img src="https://randomuser.me/api/portraits/women/60.jpg" alt="User Avatar"
                        class="w-8 h-8 rounded-full object-cover">
                    <div class="flex-1">
                        <p class="font-medium text-gray-900">u/NestedCommenter2</p>
                        <p class="text-gray-700 text-sm">
                            Agreed! It's a fantastic starting point for anyone new to Tailwind.
                        </p>
                        <div class="flex items-center space-x-2 mt-2">
                            <button class="text-gray-500 hover:text-blue-600 focus:outline-none items-center mt-1">
                                <Icon name="material-symbols:arrow-circle-up-outline" size="20"></Icon>
                            </button>
                            <span class="text-md text-gray-700">12</span>
                            <button class="text-gray-500 hover:text-red-600 focus:outline-none items-center mt-1">
                                <Icon name="material-symbols:arrow-circle-down-outline" size="20"></Icon>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>


</template>
<script>
export default {
    name: 'DiscussSection'
}
</script>