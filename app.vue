<script setup>

</script>
<template>
    <div class="greetings">
      <h1 class="green">{{ msg }}</h1>
    <h3>
      You’ve successfullly come to 總幹事六大指標 選股系統服務！
      <br />
      Visit the following websites to get more Info!
      <a href="https://shopee.tw/abedul59" target="_blank" rel="noopener">Shopee</a> +
      <a href="https://vuejs.org/" target="_blank" rel="noopener">Ruten</a>.
    </h3>
  </div>
  <br>
  <div class="center">
  <header>
    <ul>
      <li><NuxtLink to="/">Home</NuxtLink></li>
      <li><NuxtLink to="/Stock6Sign2403">Stock6Sign2403</NuxtLink></li>
      <li><NuxtLink to="/Stock6Sign2403djm">Stock6Sign2403djm</NuxtLink></li>
      <li><NuxtLink to="/Stock6Sign2403m">Stock6Sign2403m</NuxtLink></li>
      <li><NuxtLink to="/Stock6Sign2403go">Stock6Sign2403go</NuxtLink></li>
      <li><NuxtLink to="/Stock6Sign2403fm">Stock6Sign2403fm</NuxtLink></li>
    </ul>

  </header>
  <NuxtLayout>
    <NuxtPage></NuxtPage>

  </NuxtLayout>
</div>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.center {
    text-align: center;
}


h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
