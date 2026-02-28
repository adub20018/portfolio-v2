<template>
  <nav>
    <div class="left">
      <a>Adub</a>
    </div>
    <div class="right">
      <a>About</a>
      <a>Projects</a>
      <a>Experience</a>
    </div>
  </nav>
</template>

<style scoped>
nav {
  display: flex;
  justify-content: space-between;
  height: 4rem;
  padding: 0 1rem;
  align-items: center;
}
.right {
  display: flex;
  gap: 1rem;
}
a {
  font-size: 18px;
}
</style>
