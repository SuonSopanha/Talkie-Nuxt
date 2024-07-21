    <template>

        <div class="max-w-5xl mx-auto mt-12 px-4 text-center">
            <div class="w-full max-w-3xl mx-auto">
                <h1 class="text-4xl font-bold mt-2 mb-6">Helping you find your new home;<br>by simplifying the search.</h1>
                <p class="px-4 leading-relaxed">Propiti provides you with a quick, simple way to reach multiple estate
                    agents.<br>Allowing you to spend less time trawling through property portals,<br>giving you more time on
                    the other things you enjoy.
                </p>
                <p class="mb-8 mt-4 px-4 leading-relaxed">Oh, and the best bit...
                    <span class="text-[#7AB2B2] font-bold">It's free!</span>
                </p>
                <div>
                    <a class="inline-block py-4 px-8 leading-none text-white bg-[#4D869C] hover:bg-pink-600 rounded shadow text-sm font-bold"
                        href="/signup">Sign-up for free</a>
                </div>
            </div>
            <div class="relative w-full max-w-xl mx-auto bg-white rounded-full mt-4">
                <input placeholder="e.g. Blog"
                    class="rounded-full w-full h-16 bg-transparent py-2 pl-8 pr-32 outline-none border-2 border-gray-100 shadow-md hover:outline-none focus:ring-teal-200 focus:border-teal-200"
                    type="text" name="query" id="query">
                <button type="submit"
                    class="absolute inline-flex items-center h-10 px-4 py-2 text-sm text-white transition duration-150 ease-in-out rounded-full outline-none right-3 top-3 bg-[#4D869C] sm:px-6 sm:text-base sm:font-medium hover:bg-teal-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-teal-500">
                    <svg class="-ml-0.5 sm:-ml-1 mr-2 w-4 h-4 sm:h-5 sm:w-5" xmlns="http://www.w3.org/2000/svg" fill="none"
                        viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                            d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path>
                    </svg>
                    Search
                </button>
            </div>
        </div>
    </template>