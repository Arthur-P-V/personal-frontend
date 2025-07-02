<script setup lang="ts">
import BannerItem from './components/BannerItem.vue'
</script>

<template>
  <header>
    <BannerItem></BannerItem>
  </header>

  <body class="bg-forest">
    <RouterView />
    <button type="button" class="btn bg-chili">Primary</button>

  </body>
</template>

<style lang="scss">
  @import "./main.scss";
</style>
