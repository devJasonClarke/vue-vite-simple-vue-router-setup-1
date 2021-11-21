<template>
  <div>
    <h1>Home Page</h1>
    <router-link to="/about">About</router-link>
  </div>
  <h2>{{ about }}</h2>
</template>

<script setup>
// Composition API
import { ref } from "vue";

const about = ref("Go to the About Page");
</script>

<style lang="scss" scoped>

</style>
