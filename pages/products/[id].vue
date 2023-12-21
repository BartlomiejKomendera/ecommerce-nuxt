<template>
    <div class="flex">
        <div>
            <p>Product details for product with id: {{ id }}</p>
        </div>
        <div>
            <img class="mx-auto" :src="product.image" />
        </div>
    </div>
</template>

<script setup>
const { id } = useRoute().params
const { data:product } = await useFetch('https://fakestoreapi.com/products/' + id)
</script>

<style scoped>
.product-image {
    max-height: 1000px;
    max-width: 70%;
    margin: 0 auto;
}
</style>