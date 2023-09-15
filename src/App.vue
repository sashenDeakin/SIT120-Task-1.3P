<script setup>
import { RouterLink, RouterView } from "vue-router";
import NavBar from "./components/NavBar.vue";
import FooterSection from "./components/Footer.vue";
</script>

<template>
  <header>
    <NavBar />
    <nav>
      <RouterLink to="/"></RouterLink>
      <RouterLink to="/about"></RouterLink>
    </nav>
  </header>
  <FooterSection />
  <RouterView />
</template>

<style scoped></style>
