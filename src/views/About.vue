<template>
  <div>
    <h1>About Page</h1>
    <router-link to="/">Home</router-link>
  </div>
  <h2>{{ home }}</h2>
</template>

<script >
// Options API
export default {
  data: () => ({home: "Home Page, here I come!"}),
};
</script>

<style lang="scss" scoped></style>
