<template>
    <div class="flex flex-wrap justify-center mx-6">
        <div class="w-full md:w-1/4 p-4 border-r border-gray-300 flex flex-col space-y-3">
            <div class="sticky top-0">

                <div class="text-sm leading-6 bg-slate-100">
                    <figure class="relative flex flex-col-reverse bg-slate-100 rounded-lg p-6">
                        <figcaption class="flex items-center space-x-4">
                            <img src="https://images.unsplash.com/photo-1632910121591-29e2484c0259?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NzEyNjZ8MHwxfHNlYXJjaHw4fHxjb2RlcnxlbnwwfDB8fHwxNzEwMTY0NjIzfDA&ixlib=rb-4.0.3&q=80&w=1080"
                                alt="" class="flex-none w-14 h-14 rounded-full object-cover" loading="lazy"
                                decoding="async">
                            <div class="flex-auto">
                                <div class="text-base text-slate-900 font-semibold ">
                                    John Doe
                                </div>
                                <div class="mt-0.5 ">
                                    Web Developer
                                </div>
                            </div>
                        </figcaption>
                    </figure>
                </div>

                <div class="px-6 py-4 mb-6 bg-slate-100 rounded-lg shadow-lg">
                    <ul class="flex flex-col gap-6 pl-4 mt-4">
                        <li class="flex items-center gap-3">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                                stroke="currentColor" class="w-6 h-6 text-teal-500">
                                <path stroke-linecap="round" stroke-linejoin="round"
                                    d="M9.813 15.904L9 18.75l-.813-2.846a4.5 4.5 0 00-3.09-3.09L2.25 12l2.846-.813a4.5 4.5 0 003.09-3.09L9 5.25l.813 2.846a4.5 4.5 0 003.09 3.09L15.75 12l-2.846.813a4.5 4.5 0 00-3.09 3.09zM18.259 8.715L18 9.75l-.259-1.035a3.375 3.375 0 00-2.455-2.456L14.25 6l1.036-.259a3.375 3.375 0 002.455-2.456L18 2.25l.259 1.035a3.375 3.375 0 002.456 2.456L21.75 6l-1.035.259a3.375 3.375 0 00-2.456 2.456zM16.894 20.567L16.5 21.75l-.394-1.183a2.25 2.25 0 00-1.423-1.423L13.5 18.75l1.183-.394a2.25 2.25 0 001.423-1.423l.394-1.183.394 1.183a2.25 2.25 0 001.423 1.423l1.183.394-1.183.394a2.25 2.25 0 00-1.423 1.423z">
                                </path>
                            </svg>
                            <a href="http://127.0.0.1:8000/user/dashboard"
                                class="text-lg font-medium text-gray-700 hover:text-teal-500 transition-colors duration-200">
                                Dashboard
                            </a>
                        </li>

                        <li class="flex items-center gap-3">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                                stroke="currentColor" class="w-6 h-6 text-teal-500">
                                <path stroke-linecap="round" stroke-linejoin="round"
                                    d="M17.593 3.322c1.1.128 1.907 1.077 1.907 2.185V21L12 17.25 4.5 21V5.507c0-1.108.806-2.057 1.907-2.185a48.507 48.507 0 0111.186 0z">
                                </path>
                            </svg>
                            <a href="http://127.0.0.1:8000/user/study-lists"
                                class="text-lg font-medium text-gray-700 hover:text-teal-500 transition-colors duration-200">
                                Study Lists
                            </a>
                        </li>

                        <li class="flex items-center gap-3">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                                stroke="currentColor" class="w-6 h-6 text-teal-500">
                                <path stroke-linecap="round" stroke-linejoin="round"
                                    d="M19.5 14.25v-2.625a3.375 3.375 0 00-3.375-3.375h-1.5A1.125 1.125 0 0113.5 7.125v-1.5a3.375 3.375 0 00-3.375-3.375H8.25m6.75 12l-3-3m0 0l-3 3m3-3v6m-1.5-15H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 00-9-9z">
                                </path>
                            </svg>
                            <a href="http://127.0.0.1:8000/user/contribution"
                                class="text-lg font-medium text-gray-700 hover:text-teal-500 transition-colors duration-200">
                                Your contribution
                            </a>
                        </li>

                        <li class="flex items-center gap-3">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                                stroke="currentColor" class="w-6 h-6 text-teal-500">
                                <path stroke-linecap="round" stroke-linejoin="round"
                                    d="M10.343 3.94c.09-.542.56-.94 1.11-.94h1.093c.55 0 1.02.398 1.11.94l.149.894c.07.424.384.764.78.93.398.164.855.142 1.205-.108l.737-.527a1.125 1.125 0 011.45.12l.773.774c.39.389.44 1.002.12 1.45l-.527.737c-.25.35-.272.806-.107 1.204.165.397.505.71.93.78l.893.15c.543.09.94.56.94 1.109v1.094c0 .55-.397 1.02-.94 1.11l-.893.149c-.425.07-.765.383-.93.78-.165.398-.143.854.107 1.204l.527.738c.32.447.269 1.06-.12 1.45l-.774.773a1.125 1.125 0 01-1.449.12l-.738-.527c-.35-.25-.806-.272-1.203-.107-.397.165-.71.505-.781.929l-.149.894c-.09.542-.56.94-1.11.94h-1.094c-.55 0-1.019-.398-1.11-.94l-.148-.894c-.071-.424-.384-.764-.781-.93-.398-.164-.854-.142-1.204.108l-.738.527c-.447.32-1.06.269-1.45-.12l-.773-.774a1.125 1.125 0 01-.12-1.45l.527-.737c.25-.35.273-.806.108-1.204-.165-.397-.505-.71-.93-.78l-.894-.15c-.542-.09-.94-.56-.94-1.109v-1.094c0-.55.398-1.02.94-1.11l.894-.149c.424-.07.765-.383.93-.78.165-.398.143-.854-.107-1.204l-.527-.738a1.125 1.125 0 01.12-1.45l.773-.773a1.125 1.125 0 011.45-.12l.737.527c.35.25.807.272 1.204.107.397-.165.71-.505.78-.929l.15-.894z">
                                </path>
                                <path stroke-linecap="round" stroke-linejoin="round"
                                    d="M15 12a3 3 0 11-6 0 3 3 0 016 0z">
                                </path>
                            </svg>
                            <a href="http://127.0.0.1:8000/user/settings"
                                class="text-lg font-medium text-gray-700 hover:text-teal-500 transition-colors duration-200">
                                Settings
                            </a>
                        </li>

                        <form action="http://127.0.0.1:8000/auth/logout" method="POST" class="mt-4">
                            <input type="hidden" name="_token" value="ymEkCLBFpgkdaSbidUArRsdHbER5DkT6ByS3eJYb">
                            <button type="submit"
                                class="w-full text-center text-red-600 text-base font-medium px-4 py-2 hover:bg-red-200 transition-colors duration-200 rounded-md">
                                Log Out
                            </button>
                        </form>
                    </ul>
                </div>


                <div class="bg-slate-100 p-4 rounded-lg shadow-md">
                    <h2 class="text-xl font-semibold text-gray-900 mb-4">Recommended Subreddits</h2>
                    <ul role="list" class="divide-y divide-gray-200">
                        <li class="flex items-center justify-between gap-x-4 py-3">
                            <div class="flex items-center gap-x-4">
                                <img class="h-12 w-12 rounded-full object-cover"
                                    src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80"
                                    alt="Subreddit Icon">
                                <div>
                                    <p class="text-sm font-semibold text-gray-900">Leslie Alexander</p>
                                    <p class="text-xs text-gray-500">r/SubredditName</p>
                                </div>
                            </div>
                            <button type="button" class="text-sm font-medium text-teal-600 hover:text-teal-800">
                                Follow
                            </button>
                        </li>
                        <li class="flex items-center justify-between gap-x-4 py-3">
                            <div class="flex items-center gap-x-4">
                                <img class="h-12 w-12 rounded-full object-cover"
                                    src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80"
                                    alt="Subreddit Icon">
                                <div>
                                    <p class="text-sm font-semibold text-gray-900">Leslie Alexander</p>
                                    <p class="text-xs text-gray-500">r/SubredditName</p>
                                </div>
                            </div>
                            <button type="button" class="text-sm font-medium text-teal-600 hover:text-teal-800">
                                Follow
                            </button>
                        </li>
                        <li class="flex items-center justify-between gap-x-4 py-3">
                            <div class="flex items-center gap-x-4">
                                <img class="h-12 w-12 rounded-full object-cover"
                                    src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80"
                                    alt="Subreddit Icon">
                                <div>
                                    <p class="text-sm font-semibold text-gray-900">Leslie Alexander</p>
                                    <p class="text-xs text-gray-500">r/SubredditName</p>
                                </div>
                            </div>
                            <button type="button" class="text-sm font-medium text-teal-600 hover:text-teal-800">
                                Follow
                            </button>
                        </li>
                    </ul>
                </div>




            </div>
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
                <img src="https://i.pinimg.com/originals/be/9d/4f/be9d4ff6c62b56af80666d848f4674f3.jpg"
                    alt="Tailwind CSS" class="w-full h-64 object-cover rounded-lg mb-4">

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
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none"
                                        viewBox="0 0 24 24" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                            d="M14 5l7 7m0 0l-7 7m7-7H3" />
                                    </svg>
                                </button>
                                <span class="text-sm text-gray-700">12</span>
                                <button class="text-gray-500 hover:text-red-600 focus:outline-none">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none"
                                        viewBox="0 0 24 24" stroke="currentColor">
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
                                            <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none"
                                                viewBox="0 0 24 24" stroke="currentColor">
                                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                                    d="M14 5l7 7m0 0l-7 7m7-7H3" />
                                            </svg>
                                        </button>
                                        <span class="text-sm text-gray-700">5</span>
                                        <button class="text-gray-500 hover:text-red-600 focus:outline-none">
                                            <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none"
                                                viewBox="0 0 24 24" stroke="currentColor">
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
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none"
                                        viewBox="0 0 24 24" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                            d="M14 5l7 7m0 0l-7 7m7-7H3" />
                                    </svg>
                                </button>
                                <span class="text-sm text-gray-700">8</span>
                                <button class="text-gray-500 hover:text-red-600 focus:outline-none">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none"
                                        viewBox="0 0 24 24" stroke="currentColor">
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
                                            <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none"
                                                viewBox="0 0 24 24" stroke="currentColor">
                                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                                    d="M14 5l7 7m0 0l-7 7m7-7H3" />
                                            </svg>
                                        </button>
                                        <span class="text-sm text-gray-700">3</span>
                                        <button class="text-gray-500 hover:text-red-600 focus:outline-none">
                                            <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none"
                                                viewBox="0 0 24 24" stroke="currentColor">
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


            </div>

        </div>
        <div class="w-full md:w-1/4 bg-gray-100 p-4 border-l border-gray-300">
            <div class="sticky top-0">
                <!-- Sidebar Content -->
                <div class="relative isolate overflow-hidden text-center rounded-lg p-4">
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
                <div class="bg-white border border-gray-200 rounded-lg shadow-sm p-4 mt-6">
                    <h2 class="text-lg font-semibold text-gray-900 mb-4">Related Posts</h2>

                    <!-- Related Post 1 -->
                    <div class="flex items-start mb-4">
                        <img src="https://images.unsplash.com/photo-1521170665346-3f21e2291d8b" alt="Related Post Image"
                            class="w-16 h-16 object-cover rounded-md mr-4">
                        <div>
                            <h3 class="text-md font-medium text-gray-900">
                                <a href="#" class="hover:text-blue-600">Understanding Flexbox in Tailwind CSS</a>
                            </h3>
                            <p class="text-gray-500 text-sm">by u/FlexMaster</p>
                        </div>
                    </div>

                    <!-- Related Post 2 -->
                    <div class="flex items-start mb-4">
                        <img src="https://images.unsplash.com/photo-1517423440428-a5a00ad493e8" alt="Related Post Image"
                            class="w-16 h-16 object-cover rounded-md mr-4">
                        <div>
                            <h3 class="text-md font-medium text-gray-900">
                                <a href="#" class="hover:text-blue-600">Tailwind CSS Tips for Beginners</a>
                            </h3>
                            <p class="text-gray-500 text-sm">by u/TailwindGuru</p>
                        </div>
                    </div>

                    <!-- Related Post 3 -->
                    <div class="flex items-start mb-4">
                        <img src="https://images.unsplash.com/photo-1506784365847-bbad939e9335" alt="Related Post Image"
                            class="w-16 h-16 object-cover rounded-md mr-4">
                        <div>
                            <h3 class="text-md font-medium text-gray-900">
                                <a href="#" class="hover:text-blue-600">Building Responsive Layouts with Tailwind</a>
                            </h3>
                            <p class="text-gray-500 text-sm">by u/LayoutNinja</p>
                        </div>
                    </div>

                    <!-- Related Post 4 -->
                    <div class="flex items-start mb-4">
                        <img src="https://images.unsplash.com/photo-1534528741775-53994a69daeb" alt="Related Post Image"
                            class="w-16 h-16 object-cover rounded-md mr-4">
                        <div>
                            <h3 class="text-md font-medium text-gray-900">
                                <a href="#" class="hover:text-blue-600">Why Tailwind is Better Than Bootstrap</a>
                            </h3>
                            <p class="text-gray-500 text-sm">by u/DevWizard</p>
                        </div>
                    </div>

                </div>
            </div>
        </div>

    </div>
</template>