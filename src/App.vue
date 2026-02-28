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
}
</style>
