<script setup>

</script>
<template>
  <div class="center">
<HelloWorld msg="Welcome here!" />
</div>
  <br>

  <header>
    <div class="center">
    <ul>
      <li><NuxtLink to="/">Home</NuxtLink></li>
      <li><NuxtLink to="/Stock6Sign2403">Stock6Sign2403</NuxtLink></li>
      <li><NuxtLink to="/Stock6Sign2403djm">Stock6Sign2403djm</NuxtLink></li>
      <li><NuxtLink to="/Stock6Sign2403m">Stock6Sign2403m</NuxtLink></li>
      <li><NuxtLink to="/Stock6Sign2403go">Stock6Sign2403go</NuxtLink></li>
      <li><NuxtLink to="/Stock6Sign2403fm">Stock6Sign2403fm</NuxtLink></li>
    </ul>
  </div>
  </header>
  
  <NuxtLayout>
    <NuxtPage></NuxtPage>

  </NuxtLayout>

</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.center {
    text-align: center;
}



header {
  line-height: 1.5;
  max-height: 100vh;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }
}
</style>
