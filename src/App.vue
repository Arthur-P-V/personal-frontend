<script setup lang="ts">
import BannerItem from './components/BannerItem.vue'
</script>

<template>
  <header>
    <BannerItem></BannerItem>
  </header>

  <body>
    <RouterView />
  </body>

  <footer class="bg-rblack"></footer>
</template>

<style lang="scss">
@import './main.scss';
</style>
