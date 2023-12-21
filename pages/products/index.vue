<template>
    <div>
        <p class="flex justify-center page-title">Products</p>
        <div class="grid grid-cols-5 gap-4 p-7">
            <div v-for="product in products">
                <ProductCard :product="product" />
            </div>
        </div>
    </div>
</template>

<script setup>
const { data:products } = await useFetch('https://fakestoreapi.com/products')
</script>

<style lang="scss" scoped>

</style>