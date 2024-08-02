<template>

    <div class="flex flex-col min-h-screen">
        <header class="bg-[#7AB2B2] text-text-color">
            <nav class="fixed top-0 left-0 w-full z-50 bg-slate-50 border-b backdrop-blur-lg bg-opacity-80">
                <div class="mx-auto max-w-7xl px-6 sm:px-6 lg:px-8 ">
                    <div class="relative flex h-12 justify-between">
                        <div class="flex flex-1 justify-start items-center space-x-2">
                            <a class="flex flex-shrink-0 items-center" href="#">
                                <img class="block h-8 w-auto" src="https://www.svgrepo.com/show/331256/talk.svg">
                            </a>
                            <p class="font-semibold text-xl text-[#4D869C]">Talkie</p>
                        </div>
                        <div class="flex-shrink-0 flex px-2 py-2 items-center space-x-8">
                            <a class="text-[#4D869C] hover:text-indigo-700 text-sm font-medium" href="#">Login</a>
                            <a class="text-white bg-[#4D869C] hover:bg-indigo-200 inline-flex items-center justify-center px-3 py-2 border border-transparent text-sm font-medium rounded-md shadow-sm "
                                href="#">Sign up
                            </a>
                        </div>
                    </div>
                </div>
            </nav>
        </header>

        <main class="flex-grow container mx-auto py-8 bg-white mt-8">
            <slot />
        </main>

    </div>
</template>

<script>
export default {
    // You can define layout-specific methods, data, and more here if needed
}
</script>

<style scoped>
/* Additional scoped styles if needed */
</style>