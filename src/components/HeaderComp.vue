<script lang="ts">
import '../assets/main.css'
export default {
  name: 'HeaderComp'
}
</script>

<template>
  <header class="header">
    <h1>Logo</h1>

    <ul class="nav_bar">
      <li><a>Resume</a></li>
      <li><a>Projects</a></li>
      <li><a>Contact</a></li>
    </ul>

    <h1>N/D</h1>
  </header>
</template>

<style scoped>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-shrink: 0;
  align-self: stretch;
  height: 5.625rem;
  color: var(--clr-txt-primary);
}
.nav_bar {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 0;
  align-self: stretch;
  gap: 3.125rem;

}
.nav_bar li {
  display: inline-block;

}
.nav_bar a{
    font-size: 18px;
}
</style>
