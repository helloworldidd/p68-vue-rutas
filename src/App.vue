<script setup>
import HeaderComponent from "./components/HeaderComponent.vue";
</script>

<template>
  <HeaderComponent />
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/contact">Contact</router-link>
  </nav>
  <router-view />

</template>

<style scoped>
.page{
  border: 10px solid rgb(90, 90, 90);
  min-height: 100vh;
}
</style>
