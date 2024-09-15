<template>
    <div class="flex items-center space-x-4 w-full bg-slate-100 rounded-lg px-2 py-0">
        <div class="flex items-center space-x-2 my-4">
            <button class="text-gray-500 hover:text-teal-600 focus:outline-none items-center mt-1">
                <Icon name="material-symbols:arrow-circle-up-outline" size="24"></Icon>
            </button>
            <span class="text-lg text-gray-700">12</span>
            <button class="text-gray-500 hover:text-red-600 focus:outline-none items-center mt-1">
                <Icon name="material-symbols:arrow-circle-down-outline" size="24"></Icon>
            </button>
        </div>
        <button class="flex items-center text-gray-500 hover:text-teal-600 space-x-1">
            <Icon name="material-symbols:comment-rounded" size="20"></Icon>
            <span>Comments</span>
        </button>
        <button class="flex items-center text-gray-500 hover:text-teal-600 space-x-1 ">
            <Icon name="material-symbols:share" size="20"></Icon>
            <span>Share</span>
        </button>
        <button class="flex items-center text-gray-500 hover:text-teal-600 space-x-1">
            <Icon name="material-symbols:bookmark" size="20"></Icon>
            <span>Save</span>
        </button>
    </div>
</template>
<script>
export default {
    name: 'PostActions'
}
</script>