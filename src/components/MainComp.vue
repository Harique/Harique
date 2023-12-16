<script lang="ts">
import '../assets/main.css'
import IntroComp from "./IntroComp.vue"
import AboutComp from './AboutComp.vue';
export default {
    name: 'MainComp',
    components: {IntroComp, AboutComp}
}
</script>

<template>

  <main class="main">
    <IntroComp></IntroComp>
    <AboutComp></AboutComp>
  </main>
  
</template>

<style scoped>
.main{
  background: var(--clr-bg-blue);
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 1.25rem;
}
</style>
