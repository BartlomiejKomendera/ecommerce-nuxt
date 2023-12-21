<template>
    <div>
        <p class="page-title flex justify-center m-7">Welcome to</p>
        <p class="text-6xl font-bold flex justify-center m-7 text-blue-600">NuxtCommerce!</p>
        <div class="card">
            <p class="page-title flex justify-center text-center mt-14 mb-14">We offer the following products:</p>
            <div class="container flex flex-wrap justify-center gap-4">
                <NuxtLink class="w-1/5 hover:shadow-md hover:opacity-50" to="/products"><img src="\c-d-x-PDX_a_82obo-unsplash.jpg"></NuxtLink>
                <NuxtLink class="w-1/5 hover:shadow-md hover:opacity-50" to="/products"><img src="\devin-avery-BRVqq2uak4E-unsplash.jpg"></NuxtLink>
                <NuxtLink class="w-1/5 hover:shadow-md hover:opacity-50" to="/products"><img src="\domino-164_6wVEHfI-unsplash.jpg"></NuxtLink>
                <NuxtLink class="w-1/5 hover:shadow-md hover:opacity-50" to="/products"><img src="\oscar-ivan-esquivel-arteaga-ZtxED1cpB1E-unsplash.jpg"></NuxtLink>
            </div>
        </div>
    </div>
</template>

<script setup>

</script>

<style scoped>

</style>