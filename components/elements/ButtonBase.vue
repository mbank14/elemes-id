<template>
    <div>
        <button class="px-4 py-2 rounded-full hover:bg-gray-100" :class="type" :disabled="disabled">
            {{ buttonText }}
        </button>
    </div>
</template>

<style>
</style>

<script>
export default {
    name: 'ButtonBase',
    props: {
        buttonText : {
            type: String,
            require: true
        },
        style: String,
        disabled: Boolean

    },
}
</script>