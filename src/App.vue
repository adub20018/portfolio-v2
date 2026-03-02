<script setup>
import Content from "./components/Content.vue";
import Profile from "./components/Profile.vue";
</script>

<template>
  <main>
    <Profile />
    <Content />
  </main>
</template>

<style scoped>
main {
  padding: 2rem;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  gap: 1rem;
}

@media screen and (max-width: 972px) {
  main {
    flex-direction: column;
  }
}

@media screen and (max-width: 500px) {
  main {
    padding: 1rem;
  }
}
</style>
