<script setup lang="ts">
import '../assets/main.css'

</script>

<template>
  <header class="header">
    <div class="logo">
      <a>Harique.dev</a>
    </div>
    <div class="nav_bar">
      <a href="#about">About</a>
      <a href="#resume">Resume</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </div>
  </header>
</template>

<style scoped>
.header {
  display: flex;
  min-height: 4.938rem;
  height: 4.938rem;
  padding: 0rem 5rem;
  justify-content: space-between;
  align-items: center;
  align-self: stretch;
  background: var(--clr-bg-darker-blue);
  
}
.logo {
  color: var(--clr-txt-primary);
  font-size: 20px;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
}
.nav_bar {
  text-align: center;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 1.875rem;
}
.nav_bar a {
  color: var(--clr-txt-primary);
  font-size: 18px;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
  text-decoration: none;
  transition: all 0.2s linear;
}
.nav_bar a:hover{
  color: var(--clr-bg-blue);
}
</style>
