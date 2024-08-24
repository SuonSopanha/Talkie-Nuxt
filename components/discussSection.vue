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
                    <button class="text-gray-500 hover:text-blue-600 focus:outline-none">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24"
                            stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M14 5l7 7m0 0l-7 7m7-7H3" />
                        </svg>
                    </button>
                    <span class="text-sm text-gray-700">12</span>
                    <button class="text-gray-500 hover:text-red-600 focus:outline-none">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24"
                            stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M10 19l-7-7m0 0l7-7m-7 7h18" />
                        </svg>
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
                            <button class="text-gray-500 hover:text-blue-600 focus:outline-none">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24"
                                    stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                        d="M14 5l7 7m0 0l-7 7m7-7H3" />
                                </svg>
                            </button>
                            <span class="text-sm text-gray-700">5</span>
                            <button class="text-gray-500 hover:text-red-600 focus:outline-none">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24"
                                    stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                        d="M10 19l-7-7m0 0l7-7m-7 7h18" />
                                </svg>
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
                    <button class="text-gray-500 hover:text-blue-600 focus:outline-none">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24"
                            stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M14 5l7 7m0 0l-7 7m7-7H3" />
                        </svg>
                    </button>
                    <span class="text-sm text-gray-700">8</span>
                    <button class="text-gray-500 hover:text-red-600 focus:outline-none">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24"
                            stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M10 19l-7-7m0 0l7-7m-7 7h18" />
                        </svg>
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
                            <button class="text-gray-500 hover:text-blue-600 focus:outline-none">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24"
                                    stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                        d="M14 5l7 7m0 0l-7 7m7-7H3" />
                                </svg>
                            </button>
                            <span class="text-sm text-gray-700">3</span>
                            <button class="text-gray-500 hover:text-red-600 focus:outline-none">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24"
                                    stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                        d="M10 19l-7-7m0 0l7-7m-7 7h18" />
                                </svg>
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