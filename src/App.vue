<script setup>
import { RouterLink, RouterView } from "vue-router";
import NavBar from "./components/NavBar.vue";
</script>

<template>
  <header>
    <nav>
      <RouterLink to="/"></RouterLink>
    </nav>
  </header>
  <RouterView />
</template>

<style scoped></style>
