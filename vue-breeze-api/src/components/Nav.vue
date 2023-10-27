<script setup>

</script>

<template>
    <nav class="flex justify-between items-center bg-blue-500 py-2">
        <router-link :to="{ name: 'Home' }" class="text-white text-xl font-semibold mr-2">Home</router-link>
        <router-link :to="{ name: 'Login' }" class="text-white text-xl font-semibold mr-2">Login</router-link>
        <router-link :to="{ name: 'Register' }" class="text-white text-xl font-semibold">Register</router-link>
    </nav>
</template>

