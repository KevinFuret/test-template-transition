<template>
  <section class="container">
    <h1>Home</h1>
    <nuxt-link to="/about">About</nuxt-link>
    <nuxt-link to="/team">Team</nuxt-link>
  </section>
</template>

<script>

export default {
  layout: 'homepage'
};
</script>

<style>
.container {
  min-height: 100vh;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

h1{
  display: block
} 

a {
  display: block;
}
</style>

