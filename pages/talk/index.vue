<template>
    <div class="flex flex-wrap justify-center mx-6">
        <div class="w-full md:w-1/4 p-4 border-r border-gray-300 flex flex-col space-y-3">
            <SidebarMenu />
        </div>
        <div class="w-full md:w-1/2 bg-white p-4">
            <!-- Add your main content here -->
            <!-- Reddit Post Details -->

            <div class="bg-white border border-gray-200 rounded-lg shadow-sm p-6">
        <!-- Post Title -->
        <h1 class="text-2xl font-semibold text-gray-900 mb-4">
            The Ultimate Guide to Tailwind CSS
        </h1>

        <!-- Post Metadata -->
        <div class="flex items-center space-x-2 text-gray-500 text-sm mb-4">
            <span>Posted by</span>
            <span class="font-medium text-gray-900">u/JohnDoe</span>
            <span>•</span>
            <span>6 hours ago</span>
        </div>

        <!-- Post Image -->
        <img src="https://i.pinimg.com/originals/be/9d/4f/be9d4ff6c62b56af80666d848f4674f3.jpg" alt="Tailwind CSS"
            class="w-full h-64 object-cover rounded-lg mb-4">

        <!-- Post Content -->
        <p class="text-gray-700 text-base leading-relaxed mb-4">
            Tailwind CSS is a utility-first CSS framework that provides a great way to style your websites
            without writing a lot of custom CSS. In this guide, we'll explore how to use Tailwind CSS to build
            modern and responsive websites.
        </p>

        <!-- Upvote/Downvote Buttons -->
        <div class="flex items-center space-x-4 mb-4">
            <button class="flex items-center text-gray-500 hover:text-blue-600 space-x-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24"
                    stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                        d="M14 5l7 7m0 0l-7 7m7-7H3" />
                </svg>
                <span>120</span>
            </button>
            <button class="flex items-center text-gray-500 hover:text-red-600 space-x-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24"
                    stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                        d="M10 19l-7-7m0 0l7-7m-7 7h18" />
                </svg>
            </button>
        </div>

        <!-- Post Actions -->
        <div class="flex items-center space-x-4 w-full">
            <button class="flex items-center text-gray-500 hover:text-blue-600 space-x-1">
                <Icon name="material-symbols:comment-rounded" size="20"></Icon>
                <span>Comments</span>
            </button>
            <button class="flex items-center text-gray-500 hover:text-blue-600">
                <Icon name="material-symbols:share" size="20"></Icon>
                <span>Share</span>
            </button>
            <button class="flex items-center text-gray-500 hover:text-blue-600">
                <Icon name="material-symbols:bookmark" size="20"></Icon>
                <span>Save</span>
            </button>
        </div>

        <DiscussSection/>


    </div>

        </div>
        <div class="w-full md:w-1/4 p-4 border-l border-gray-300">
            <div class="sticky top-0">
                <!-- Sidebar Content -->
                <div class="relative isolate overflow-hidden bg-gray-100 text-center rounded-lg p-4">
                    <h2 class="font-bold text-xl uppercase tracking-wide sm:text-2xl">
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
                <RelatedPost/>


            </div>
        </div>

    </div>
</template>