<script setup lang="ts">
import BannerItem from './components/BannerItem.vue'
</script>

<template>
  <header>
    <BannerItem></BannerItem>
  </header>

  <RouterView />
</template>

<style>
body {
  background-color: burlywood;
}
</style>
