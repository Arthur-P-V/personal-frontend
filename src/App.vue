<script setup lang="ts">
import BannerItem from './components/BannerItem.vue'
import FooterItem from './components/FooterItem.vue'
</script>

<template>
  <header>
    <BannerItem></BannerItem>
  </header>

  <body>
    <RouterView />
  </body>

  <footer class="bg-rblack"><FooterItem /></footer>
</template>

<style lang="scss">
@import './main.scss';
</style>
