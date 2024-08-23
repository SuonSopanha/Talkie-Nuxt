<template>

    <div class="ml-4 w-full">
        <div class="flex items-center justify-between mb-3">
            <h3 class="text-xl font-semibold text-gray-900">Post Title</h3>
            <span class="text-sm text-gray-500">Posted by u/username</span>
        </div>
        <p class="text-gray-700 mb-4">
            This is a brief summary of the post content. It can be text, a link, an image, or a
            combination of these.
        </p>
        <div class="flex items-center space-x-4">
            <button class="flex items-center text-gray-500 hover:text-teal-600 space-x-1">
                <Icon name="material-symbols:comment-rounded" size="20"></Icon>
                <span>Comments</span>
            </button>
            <button class="flex items-center text-gray-500 hover:text-teal-600 space-x-1">
                <Icon name="material-symbols:share" size="20"></Icon>
                <span>Share</span>
            </button>
            <button class="flex items-center text-gray-500 hover:text-teal-600 space-x-1">
                <Icon name="material-symbols:bookmark" size="20"></Icon>
                <span>Save</span>
            </button>
        </div>
    </div>

</template>

<script>
export default {
    name: 'FeedCard'
}
</script>