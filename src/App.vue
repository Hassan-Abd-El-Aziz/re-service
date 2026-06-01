<template>
    <div>
        <NavBar />
        <Hero />
        <About />
    </div>
</template>
<script setup>
import { onMounted } from 'vue';
import NavBar from './components/NavBar.vue';
import Hero from './components/Hero.vue';
import About from './components/About.vue';

import AOS from 'aos';
import 'aos/dist/aos.css';
onMounted(() => {
    AOS.init({
        duration: 100,
        easing: 'ease-in-out',
        once: true,
        offset: 100
    })
})
</script>