<template>
  <nav>
    <ul>
      <li><router-link to="/">Home</router-link></li>
      <li><router-link to="/about">About</router-link></li>
      <li><router-link to="/contact">Contact</router-link></li>
    </ul>
  </nav>
</template>

<style scoped>
nav {
  padding: 1rem;
  background: #f0f0f0;
}
ul {
  display: flex;
  gap: 1rem;
  list-style: none;
  padding: 0;
}
a {
  text-decoration: none;
  color: #333;
}
</style>