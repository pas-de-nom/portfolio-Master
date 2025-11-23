<script setup>
import Navbar from './components/Navbar.vue';
import Hero from './components/Hero.vue';
import Skills from './components/skills.vue';
import Projet from './components/projet.vue';
import Footer from './components/Footer.vue';

</script>

<template class="m-0 ">
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

  <div>
    <Navbar/>
  </div>
  <Hero />
  <skills/>
  <projet/>
  <Footer/>

</template>