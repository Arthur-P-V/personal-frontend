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

  <footer class="bg-forest"></footer>
</template>

<style lang="scss">
  @import "./main.scss";

  body {
    min-height:100vh;
  }


</style>
