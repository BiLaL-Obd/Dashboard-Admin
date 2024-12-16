<script setup>
import Header from './components/Header.vue';
</script>

<template>
  <Header>
    <RouterView />
  </Header>
</template>

<style lang="scss">
// As we are using `layouts` plugin we need its styles to be imported
@use "@layouts/styles/default-layout";
</style>
