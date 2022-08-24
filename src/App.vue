<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="@/assets/56155cf4-e4ef-487b-a657-b05191d702de.jpg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="Ariq Fadhlurrahman" />

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">Skill</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>

.foto{
  background-color: aqua;
  width: 175px;
  height: 175px;
  border-radius: 50%;
  margin-left: 3rem;
  margin-right: -5rem;
}

img{
  border-radius: 50%;
  width: 185px;
  height: 185px;
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
