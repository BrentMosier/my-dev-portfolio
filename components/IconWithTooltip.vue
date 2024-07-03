<template>
    <UTooltip :text="tooltipText">
        <Icon :name="iconName" size="48px" class="text-gray-400 hover:text-gray-200" />
    </UTooltip>
</template>

<script setup>
defineProps({iconName:{type:String, default:""}, tooltipText:{type:String, default:""}})

</script>