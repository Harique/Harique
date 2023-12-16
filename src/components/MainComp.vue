<script lang="ts">
import '../assets/main.css'
import IntroComp from "./IntroComp.vue"
import AboutComp from './AboutComp.vue';
import ResumeComp from './ResumeComp.vue';
export default {
    name: 'MainComp',
    components: {IntroComp, AboutComp,ResumeComp}
}
</script>

<template>

  <main class="main">
    <IntroComp></IntroComp>
    <div class="white_part">
      <AboutComp></AboutComp>
      <ResumeComp></ResumeComp>
    </div>
    
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
.white_part{
  width: 100%;
  margin: 0;
  background: var(--clr-bg);
}
</style>
