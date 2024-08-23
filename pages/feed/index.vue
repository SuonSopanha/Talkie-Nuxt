<script setup lang="ts">
import FeedCard from '../../components/feedCard.vue';


</script>

<template>
    <div class="flex flex-wrap justify-center mx-6">
        <div class="w-full md:w-1/4 p-4 border-r border-gray-300 flex flex-col space-y-3">
            <SidebarMenu />
        </div>
        <div class="w-full md:w-1/2 bg-white p-4">
            <!-- Add your main content here -->
            <div id="search-bar" class="bg-white rounded-md shadow-md p-4">
                <form class="flex items-center">
                    <input type="text" placeholder="Search here"
                        class="w-full rounded-md px-4 py-2 border border-gray-300 focus:outline-none focus:ring-2 focus:ring-teal-500 focus:border-teal-500 transition duration-200">
                    <button type="submit"
                        class="bg-teal-600 text-white rounded-md px-4 py-2 ml-2 hover:bg-teal-700 focus:outline-none focus:ring-2 focus:ring-teal-500 transition duration-200">
                        <div class="flex items-center space-x-2">
                            <Icon name="material-symbols:add-comment-rounded" size="20"></Icon>
                            <p>Talk</p>
                        </div>
                    </button>
                    <button type="submit"
                        class="bg-teal-600 text-white rounded-md px-4 py-2 ml-2 hover:bg-teal-700 focus:outline-none focus:ring-2 focus:ring-teal-500 transition duration-200">
                        <div class="flex items-center space-x-2">
                            <Icon name="material-symbols:imagesmode-rounded" size="20"></Icon>
                            <p>Image</p>
                        </div>
                    </button>
                </form>
            </div>

            <!-- Navigation Buttons -->
            <div class="space-y-4 my-4">
                <!-- Navigation Section 1 -->
                <div class="text-center">
                    <div class="grid grid-cols-1 sm:grid-cols-3 gap-2">
                        <button
                            class="bg-teal-600 text-white p-2 rounded-lg shadow-md flex items-center justify-center space-x-2 text-sm hover:bg-teal-700 focus:outline-none focus:ring-2 focus:ring-teal-500 transition duration-200">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24"
                                stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                    d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6" />
                            </svg>
                            <span class="text-xs">Home</span>
                        </button>
                        <button
                            class="bg-white text-teal-600 p-2 rounded-lg shadow-md flex items-center justify-center space-x-2 text-sm hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-teal-500 transition duration-200">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24"
                                stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                    d="M5.121 17.804A13.937 13.937 0 0112 16c2.5 0 4.847.655 6.879 1.804M15 10a3 3 0 11-6 0 3 3 0 016 0zm6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                            </svg>
                            <span class="text-xs">Profile</span>
                        </button>
                        <button
                            class="bg-white text-teal-600 p-2 rounded-lg shadow-md flex items-center justify-center space-x-2 text-sm hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-teal-500 transition duration-200">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24"
                                stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                    d="M17 8h2a2 2 0 012 2v6a2 2 0 01-2 2h-2v4l-4-4H9a1.994 1.994 0 01-1.414-.586m0 0L11 14h4a2 2 0 002-2V6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2v4l.586-.586z" />
                            </svg>
                            <span class="text-xs">Messages</span>
                        </button>
                        <button
                            class="bg-white text-teal-600 p-2 rounded-lg shadow-md flex items-center justify-center space-x-2 text-sm hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-teal-500 transition duration-200">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24"
                                stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                    d="M5.121 17.804A13.937 13.937 0 0112 16c2.5 0 4.847.655 6.879 1.804M15 10a3 3 0 11-6 0 3 3 0 016 0zm6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                            </svg>
                            <span class="text-xs">Profile</span>
                        </button>
                        <button
                            class="bg-white text-teal-600 p-2 rounded-lg shadow-md flex items-center justify-center space-x-2 text-sm hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-teal-500 transition duration-200">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24"
                                stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                    d="M17 8h2a2 2 0 012 2v6a2 2 0 01-2 2h-2v4l-4-4H9a1.994 1.994 0 01-1.414-.586m0 0L11 14h4a2 2 0 002-2V6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2v4l.586-.586z" />
                            </svg>
                            <span class="text-xs">Messages</span>
                        </button>
                    </div>
                </div>



            </div>


            <!-- Posts -->
            <div class="space-y-6">
                <!-- Post Item -->
                <div class="bg-white border border-gray-200 rounded-lg shadow-lg overflow-hidden">
                    <div class="flex p-4">
                        <!-- Voting Section -->
                        <div class="flex flex-col items-center justify-center space-y-2">
                            <button class="text-gray-500 hover:text-teal-600">
                                <Icon name="material-symbols:arrow-circle-up-outline-rounded" size="24"></Icon>
                            </button>
                            <span class="text-gray-700 font-semibold">123</span>
                            <button class="text-gray-500 hover:text-red-600">
                                <Icon name="material-symbols:arrow-circle-down-outline-rounded" size="24"></Icon>
                            </button>
                        </div>
                        <!-- Post Content -->
                        <!-- FeedCard -->
                        <FeedCard />
                    </div>
                </div>

                <!-- Repeat Post Item for more posts -->
                <!-- ... -->
            </div>


        </div>
        <div class="w-full md:w-1/4 bg-gray-100 p-4 border-l border-gray-300">
            <div class="sticky top-0">
                <!-- Add your sidebar content here -->
                <div class="relative isolate overflow-hidden text-center rounded-lg p-4">
                    <h2 class="font-nudge-extrabold text-xl font-bold uppercase tracking-wide sm:text-2xl">
                        Join our community now
                    </h2>
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
                        <span class="!ml-2 font-bold italic text-teal-500">Join these awesome members</span>
                    </div>
                    <div class="mt-6 flex items-center justify-center">
                        <button type="button"
                            class="text-sm relative inline-flex items-center gap-x-2 rounded-lg bg-teal-600 px-4 py-2 font-semibold text-white shadow-sm hover:bg-teal-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-teal-600">
                            <span class="absolute -top-4 left-0 w-full text-left text-xs italic text-teal-600">No
                                Obligations</span>
                            Join Now
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"
                                aria-hidden="true" class="-mr-0.5 h-4 w-4">
                                <path fill-rule="evenodd"
                                    d="M16.72 7.72a.75.75 0 011.06 0l3.75 3.75a.75.75 0 010 1.06l-3.75 3.75a.75.75 0 11-1.06-1.06l2.47-2.47H3a.75.75 0 010-1.5h16.19l-2.47-2.47a.75.75 0 010-1.06z"
                                    clip-rule="evenodd"></path>
                            </svg>
                        </button>
                    </div>
                    <svg viewBox="0 0 1024 1024"
                        class="absolute left-1/2 top-1/2 -z-10 h-[36rem] w-[36rem] -translate-x-1/2 [mask-image:radial-gradient(closest-side,white,transparent)]"
                        aria-hidden="true">
                        <circle cx="512" cy="512" r="512" fill="url(#827591b1-ce8c-4110-b064-7cb85a0b1217)"
                            fill-opacity="0.7"></circle>
                        <defs>
                            <radialGradient id="827591b1-ce8c-4110-b064-7cb85a0b1217">
                                <stop stop-color="#15b8a6"></stop>
                                <stop offset="1" stop-color="#15b8a6"></stop>
                            </radialGradient>
                        </defs>
                    </svg>
                </div>
            </div>
        </div>
    </div>
</template>