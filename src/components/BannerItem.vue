<template>
  <nav class="navbar navbar-expand-lg bg-rblack">
    <div class="container-fluid">
      <RouterLink class="navbar-brand" to="/"
        ><img src="/src/logo-placeholder.png" alt=""
      /></RouterLink>
      <ul class="navbar-nav me-auto">
        <li class="nav-item h2"><RouterLink class="nav-link text-forest" to="/">Home</RouterLink></li>
        <li class="nav-item h2"><RouterLink class="nav-link text-forest" to="about">About</RouterLink></li>
        <li class="nav-item h2"><RouterLink class="nav-link text-forest" to="Posts">Posts</RouterLink></li>
        <li class="nav-item h2"><RouterLink class="nav-link text-forest" to="Projects">Projects</RouterLink></li>
        <li class="nav-item h2"><RouterLink class="nav-link text-forest" to="Games">Games</RouterLink></li>
      </ul>
    </div>
  </nav>
</template>

<style scoped>
</style>
