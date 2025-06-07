<template>
  <h1>
    <RouterLink to="/"><img src="/src/logo-placeholder.png" alt="" /></RouterLink>
  </h1>
  <div class="navbar">
    <nav>
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="about">About</RouterLink>
      <RouterLink to="test">Test</RouterLink>
    </nav>
  </div>
</template>

<style scoped>
a {
  text-decoration: none;
  color: darkgreen;
}
</style>
