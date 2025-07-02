<template>
  <h1 style="font-weight: bolder; padding-left: 0.5em">AWPV.dev</h1>
  <nav class="navbar navbar-expand-lg bg-tea">
    <div class="container-fluid">
      <RouterLink class="navbar-brand" to="/"
        ><img src="/src/logo-placeholder.png" alt=""
      /></RouterLink>
      <ul class="navbar-nav me-auto">
        <li class="nav-item h2"><RouterLink class="nav-link" to="/">Home</RouterLink></li>
        <li class="nav-item h2"><RouterLink class="nav-link" to="about">About</RouterLink></li>
        <li class="nav-item h2"><RouterLink class="nav-link" to="test">Test</RouterLink></li>
      </ul>
    </div>
  </nav>
</template>

<style scoped>
a {
  font-weight: bolder;
  text-decoration: none;
  color: darkblue;
}
</style>
