<template>
    <header>
        <nav class="container p-4 shadow-md flex justify-between mx-auto font-mono">
            <NuxtLink to="/" class="text-lg font-bold">NuxtCommerce</NuxtLink>
            <ul class="flex gap-3">
                <li>
                    <NuxtLink to="/">Home</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/about">About</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/products">Products</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/account">Account</NuxtLink>
                </li>
            </ul>
        </nav>
    </header>
    <div class="container p-5 mx-auto font-mono">
        <slot />
    </div>
</template>

<script setup>

</script>

<style scoped>
.router-link-exact-active {
    color: blue;
}
</style>