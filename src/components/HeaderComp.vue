<script lang="ts">
import '../assets/main.css'
export default {
  name: 'HeaderComp'
}
</script>

<template>
  <header class="header">
    <div class="logo">
      <a>Harique.dev</a>
    </div>
    <div class="nav_bar">
      <a>About</a>
      <a>Resume</a>
      <a>Projects</a>
      <a>Contact</a>
    </div>
  </header>
</template>

<style scoped>
.header{
  display: flex;
  min-height: 4.938rem;
  height: 4.938rem;
  padding: 0rem 5rem ;
  justify-content: space-between;
  align-items: center;
  align-self: stretch;
  background: var(--clr-bg-blue);
}
.logo{
  color: var(--clr-txt-primary);
  font-size: 20px;
  font-style: normal;
  font-weight: 500;
  line-height: normal
}
.nav_bar{
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
  line-height: normal
}
</style>
