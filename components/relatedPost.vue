<template>
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
</template>
<script>
export default {
    name: 'RelatedPost'
}
</script>