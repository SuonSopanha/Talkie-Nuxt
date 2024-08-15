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
                                stroke="currentColor" class="w-6 h-6 text-blue-500">
                                <path stroke-linecap="round" stroke-linejoin="round"
                                    d="M9.813 15.904L9 18.75l-.813-2.846a4.5 4.5 0 00-3.09-3.09L2.25 12l2.846-.813a4.5 4.5 0 003.09-3.09L9 5.25l.813 2.846a4.5 4.5 0 003.09 3.09L15.75 12l-2.846.813a4.5 4.5 0 00-3.09 3.09zM18.259 8.715L18 9.75l-.259-1.035a3.375 3.375 0 00-2.455-2.456L14.25 6l1.036-.259a3.375 3.375 0 002.455-2.456L18 2.25l.259 1.035a3.375 3.375 0 002.456 2.456L21.75 6l-1.035.259a3.375 3.375 0 00-2.456 2.456zM16.894 20.567L16.5 21.75l-.394-1.183a2.25 2.25 0 00-1.423-1.423L13.5 18.75l1.183-.394a2.25 2.25 0 001.423-1.423l.394-1.183.394 1.183a2.25 2.25 0 001.423 1.423l1.183.394-1.183.394a2.25 2.25 0 00-1.423 1.423z">
                                </path>
                            </svg>
                            <a href="http://127.0.0.1:8000/user/dashboard"
                                class="text-lg font-medium text-gray-700 hover:text-blue-500 transition-colors duration-200">
                                Dashboard
                            </a>
                        </li>

                        <li class="flex items-center gap-3">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                                stroke="currentColor" class="w-6 h-6 text-blue-500">
                                <path stroke-linecap="round" stroke-linejoin="round"
                                    d="M17.593 3.322c1.1.128 1.907 1.077 1.907 2.185V21L12 17.25 4.5 21V5.507c0-1.108.806-2.057 1.907-2.185a48.507 48.507 0 0111.186 0z">
                                </path>
                            </svg>
                            <a href="http://127.0.0.1:8000/user/study-lists"
                                class="text-lg font-medium text-gray-700 hover:text-blue-500 transition-colors duration-200">
                                Study Lists
                            </a>
                        </li>

                        <li class="flex items-center gap-3">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                                stroke="currentColor" class="w-6 h-6 text-blue-500">
                                <path stroke-linecap="round" stroke-linejoin="round"
                                    d="M19.5 14.25v-2.625a3.375 3.375 0 00-3.375-3.375h-1.5A1.125 1.125 0 0113.5 7.125v-1.5a3.375 3.375 0 00-3.375-3.375H8.25m6.75 12l-3-3m0 0l-3 3m3-3v6m-1.5-15H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 00-9-9z">
                                </path>
                            </svg>
                            <a href="http://127.0.0.1:8000/user/contribution"
                                class="text-lg font-medium text-gray-700 hover:text-blue-500 transition-colors duration-200">
                                Your contribution
                            </a>
                        </li>

                        <li class="flex items-center gap-3">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                                stroke="currentColor" class="w-6 h-6 text-blue-500">
                                <path stroke-linecap="round" stroke-linejoin="round"
                                    d="M10.343 3.94c.09-.542.56-.94 1.11-.94h1.093c.55 0 1.02.398 1.11.94l.149.894c.07.424.384.764.78.93.398.164.855.142 1.205-.108l.737-.527a1.125 1.125 0 011.45.12l.773.774c.39.389.44 1.002.12 1.45l-.527.737c-.25.35-.272.806-.107 1.204.165.397.505.71.93.78l.893.15c.543.09.94.56.94 1.109v1.094c0 .55-.397 1.02-.94 1.11l-.893.149c-.425.07-.765.383-.93.78-.165.398-.143.854.107 1.204l.527.738c.32.447.269 1.06-.12 1.45l-.774.773a1.125 1.125 0 01-1.449.12l-.738-.527c-.35-.25-.806-.272-1.203-.107-.397.165-.71.505-.781.929l-.149.894c-.09.542-.56.94-1.11.94h-1.094c-.55 0-1.019-.398-1.11-.94l-.148-.894c-.071-.424-.384-.764-.781-.93-.398-.164-.854-.142-1.204.108l-.738.527c-.447.32-1.06.269-1.45-.12l-.773-.774a1.125 1.125 0 01-.12-1.45l.527-.737c.25-.35.273-.806.108-1.204-.165-.397-.505-.71-.93-.78l-.894-.15c-.542-.09-.94-.56-.94-1.109v-1.094c0-.55.398-1.02.94-1.11l.894-.149c.424-.07.765-.383.93-.78.165-.398.143-.854-.107-1.204l-.527-.738a1.125 1.125 0 01.12-1.45l.773-.773a1.125 1.125 0 011.45-.12l.737.527c.35.25.807.272 1.204.107.397-.165.71-.505.78-.929l.15-.894z">
                                </path>
                                <path stroke-linecap="round" stroke-linejoin="round"
                                    d="M15 12a3 3 0 11-6 0 3 3 0 016 0z">
                                </path>
                            </svg>
                            <a href="http://127.0.0.1:8000/user/settings"
                                class="text-lg font-medium text-gray-700 hover:text-blue-500 transition-colors duration-200">
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


                <div class=" bg-slate-100">
                    <ul role="list" class="divide-y divide-gray-100 bg-slate-100 ml-2">
                        <li class="flex items-center justify-between gap-x-6 py-2 m-2">
                            <div class="flex min-w-0 gap-x-4 items-center">
                                <img class="h-12 w-12 flex-none rounded-full bg-gray-50"
                                    src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80"
                                    alt="">
                                <div class="min-w-0 flex-auto">
                                    <p class="text-sm font-semibold leading-6 text-gray-900">Leslie Alexander</p>
                                </div>
                            </div>
                            <button type="submit" class="rounded-xl px-2 m-2 border border-gray-600 h-10">
                                <div class="flex items-center">
                                    <p class="text-sm">Image</p>
                                </div>

                            </button>
                        </li>
                        <li class="flex items-center justify-between gap-x-6 py-2 m-2">
                            <div class="flex min-w-0 gap-x-4 items-center">
                                <img class="h-12 w-12 flex-none rounded-full bg-gray-50"
                                    src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80"
                                    alt="">
                                <div class="min-w-0 flex-auto">
                                    <p class="text-sm font-semibold leading-6 text-gray-900">Leslie Alexander</p>
                                </div>
                            </div>
                            <button type="submit" class="rounded-xl px-2 m-2 border border-gray-600 h-10">
                                <div class="flex items-center">
                                    <p class="text-sm">Image</p>
                                </div>

                            </button>
                        </li>
                        <li class="flex items-center justify-between gap-x-6 py-2 m-2">
                            <div class="flex min-w-0 gap-x-4 items-center">
                                <img class="h-12 w-12 flex-none rounded-full bg-gray-50"
                                    src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80"
                                    alt="">
                                <div class="min-w-0 flex-auto">
                                    <p class="text-sm font-semibold leading-6 text-gray-900">Leslie Alexander</p>
                                </div>
                            </div>
                            <button type="submit" class="rounded-xl px-2 m-2 border border-gray-600 h-10">
                                <div class="flex items-center">
                                    <p class="text-sm">Image</p>
                                </div>

                            </button>
                        </li>
                    </ul>
                </div>

            </div>
        </div>
        <div class="w-full md:w-1/2 bg-white p-4">
            <!-- Add your main content here -->
            <div id="search-bar" class="w-120 bg-white rounded-md shadow-lg z-10">
                <form class="flex items-center justify-center p-2">
                    <input type="text" placeholder="Search here"
                        class="w-full rounded-md px-2 py-1 focus:outline-none focus:ring-2 focus:ring-gray-600 focus:border-transparent">
                    <button type="submit"
                        class="bg-gray-800 text-white rounded-md px-4 py-1 ml-2 hover:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-gray-600 focus:ring-opacity-50">

                        <div class="flex space-x-2 items-center">
                            <Icon name="material-symbols:add-comment-rounded" size="20"></Icon>
                            <p>Talk</p>
                        </div>
                    </button>
                    <button type="submit"
                        class="bg-gray-800 text-white rounded-md px-4 py-1 ml-2 hover:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-gray-600 focus:ring-opacity-50">
                        <div class="flex space-x-2 items-center">
                            <Icon name="material-symbols:imagesmode-rounded" size="20"></Icon>
                            <p>Image</p>
                        </div>

                    </button>
                </form>

            </div>

            <div>
                <div class="grid grid-cols-3 gap-5"> <button
                        class="text-white p-4 rounded bg-indigo-500 shadow-md flex items-center justify-center"> <svg
                            xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2" fill="none" viewBox="0 0 24 24"
                            stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6" />
                        </svg> Home </button> <button
                        class="p-4 rounded bg-white text-indigo-500 shadow-md flex items-center justify-center"> <svg
                            xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2" fill="none" viewBox="0 0 24 24"
                            stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M5.121 17.804A13.937 13.937 0 0112 16c2.5 0 4.847.655 6.879 1.804M15 10a3 3 0 11-6 0 3 3 0 016 0zm6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                        </svg> Profile </button> <button
                        class="p-4 rounded bg-white text-indigo-500 shadow-md flex items-center justify-center"> <svg
                            xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2" fill="none" viewBox="0 0 24 24"
                            stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M17 8h2a2 2 0 012 2v6a2 2 0 01-2 2h-2v4l-4-4H9a1.994 1.994 0 01-1.414-.586m0 0L11 14h4a2 2 0 002-2V6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2v4l.586-.586z" />
                        </svg> Profile </button> </div>

            </div>

            <div class="max-w-md mx-auto bg-white border border-gray-200 rounded-lg shadow-lg overflow-hidden">
                <div class="flex items-start p-4">
                    <!-- Voting Section -->
                    <div class="flex flex-col items-center justify-start">
                        <button class="text-gray-500 hover:text-red-600 mb-1">
                            <Icon name="material-symbols:arrow-circle-up-outline-rounded" size="24"></Icon>
                        </button>
                        <span class="text-gray-700 font-semibold">123</span>
                        <button class="text-gray-500 hover:text-blue-600 mt-1">
                            <Icon name="material-symbols:arrow-circle-down-outline-rounded" size="24"></Icon>
                        </button>
                    </div>
                    <!-- Post Content -->
                    <div class="ml-4 w-full">
                        <div class="flex items-center justify-between mb-2">
                            <h3 class="text-xl font-semibold text-gray-900">Post Title</h3>
                            <span class="text-sm text-gray-500">Posted by u/username</span>
                        </div>
                        <p class="text-gray-700 mb-4">
                            This is a brief summary of the post content. It can be text, a link, an image, or a
                            combination of these.
                        </p>
                        <div class="flex items-center space-x-4">
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
                    </div>
                </div>
            </div>

            <div class="max-w-md mx-auto bg-white border border-gray-200 rounded-lg shadow-lg overflow-hidden">
                <div class="flex items-start p-4">
                    <!-- Voting Section -->
                    <div class="flex flex-col items-center justify-start">
                        <button class="text-gray-500 hover:text-red-600 mb-1">
                            <Icon name="material-symbols:arrow-circle-up-outline-rounded" size="24"></Icon>
                        </button>
                        <span class="text-gray-700 font-semibold">123</span>
                        <button class="text-gray-500 hover:text-blue-600 mt-1">
                            <Icon name="material-symbols:arrow-circle-down-outline-rounded" size="24"></Icon>
                        </button>
                    </div>
                    <!-- Post Content -->
                    <div class="ml-4 w-full">
                        <div class="flex items-center justify-between mb-2">
                            <h3 class="text-xl font-semibold text-gray-900">Post Title</h3>
                            <span class="text-sm text-gray-500">Posted by u/username</span>
                        </div>
                        <p class="text-gray-700 mb-4">
                            This is a brief summary of the post content. It can be text, a link, an image, or a
                            combination of these.
                        </p>
                        <div class="flex items-center space-x-4">
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
                    </div>
                </div>
            </div>

            <div class="max-w-md mx-auto bg-white border border-gray-200 rounded-lg shadow-lg overflow-hidden">
                <div class="flex items-start p-4">
                    <!-- Voting Section -->
                    <div class="flex flex-col items-center justify-start">
                        <button class="text-gray-500 hover:text-red-600 mb-1">
                            <Icon name="material-symbols:arrow-circle-up-outline-rounded" size="24"></Icon>
                        </button>
                        <span class="text-gray-700 font-semibold">123</span>
                        <button class="text-gray-500 hover:text-blue-600 mt-1">
                            <Icon name="material-symbols:arrow-circle-down-outline-rounded" size="24"></Icon>
                        </button>
                    </div>
                    <!-- Post Content -->
                    <div class="ml-4 w-full">
                        <div class="flex items-center justify-between mb-2">
                            <h3 class="text-xl font-semibold text-gray-900">Post Title</h3>
                            <span class="text-sm text-gray-500">Posted by u/username</span>
                        </div>
                        <p class="text-gray-700 mb-4">
                            This is a brief summary of the post content. It can be text, a link, an image, or a
                            combination of these.
                        </p>
                        <div class="flex items-center space-x-4">
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
                    </div>
                </div>
            </div>


        </div>
        <div class="w-full md:w-1/4 bg-gray-100 p-4 border-l border-gray-300">
            <div class="sticky top-0">
                <!-- Add your sidebar content here -->
                Sidebar
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



                <div class="flex px-3 py-3">
                    <div class="max-w-sm rounded overflow-hidden shadow-lg">
                        <img class="w-full" src="https://tailwindcss.com/img/card-top.jpg"
                            alt="Sunset in the mountains">
                        <div class="px-6 py-4">
                            <div class="font-bold text-xl mb-2">The Coldest Sunset</div>
                            <p class="text-gray-700 text-base">
                                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus quia, nulla!
                                Maiores et
                                perferendis eaque, exercitationem praesentium nihil.
                            </p>
                        </div>
                        <div class="px-6 py-4">
                            <span
                                class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2">#photography</span>
                            <span
                                class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2">#travel</span>
                            <span
                                class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700">#winter</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>