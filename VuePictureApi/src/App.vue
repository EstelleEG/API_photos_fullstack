<script setup>
import { RouterLink,RouterView } from 'vue-router'
import Navbar from '@/components/Navbar.vue'
import Footer from '@/components/Footer.vue'
</script>

<template>
<header>
<Navbar />
</header>
<RouterView />
<Footer msg="All rights reserved. Coded by SHARVANI STUDIO" />
</template>

<style></style>
