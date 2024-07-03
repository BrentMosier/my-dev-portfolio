<template>
    <div class="p-8 border-2 border-solid border-green-600">
        <div class="flex justify-center pb-8">{{title}}</div>
        <div class="flex flex-row flex-wrap justify-around">
            <slot/>
        </div>
    </div>

</template>

<script setup>
const props = defineProps(["title"]);
</script>