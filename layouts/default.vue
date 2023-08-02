<template>
    <div>
        <header class="shadow-sm  bg-white">
            <nav class="container mx-auto p-4 flex justify-between">
                <NuxtLink to="/" class="font-bold">NUXT APP</NuxtLink>
                <ul class="flex gap-4">
                    <li><NuxtLink to="/">home</NuxtLink></li>
                    <li><NuxtLink to="/about">about</NuxtLink></li>
                    <li><NuxtLink to="/products">products</NuxtLink></li>
                </ul>
            </nav>
        </header>

        <!-- output page content -->

        <div class="container x-auto p-4">
            <slot />
        </div>
    </div>
</template>

<style scoped>
.router-link-exact-active {
    color: #12b488;
}
</style>