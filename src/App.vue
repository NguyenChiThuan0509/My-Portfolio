<script setup>
import Header from "./components/Header.vue"
import HelloWorld from './components/HelloWorld.vue'
import Left from './components/Left.vue'
</script>

<template>
  <!-- #0 -->
  <Header />
  <!-- #1 -->
  <div>
    <a href="/">
      <img src="./assets/Jon..png" class="logo" alt="web logo">
    </a>
  </div>
  <!-- #2 -->
  <HelloWorld msg="Call me Jon." />
  <!-- #3 -->
  <Left msg="Let's explore" />
</template>

<style scoped>
.logo {
  height: 10em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;

  border-radius: 50%;
  /* bo logo */
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
</style>
