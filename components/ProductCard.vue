<template>
    <div class="card text-center p-4">
        <img class="thumb" :src="product.image" />
        <p class="m-4 truncate">{{ product.title }}</p>
        <NuxtLink class="p-3 rounded-md bg-sky-800 text-white hover:cursor-pointer" :to="`/products/${product.id}`">
            Product Details</NuxtLink>
    </div>
</template>

<script setup>
const { product } = defineProps(['product'])
</script>

<style scoped>
.thumb {
    max-height: 100px;
    max-width: 70%;
    margin: 0 auto;
}
</style>