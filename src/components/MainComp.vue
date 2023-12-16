<script lang="ts">
import '../assets/main.css'
import IntroComp from "./IntroComp.vue"
export default {
    name: 'MainComp',
    components: {IntroComp}
}
</script>

<template>

  <main class="main">
    <IntroComp></IntroComp>
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
