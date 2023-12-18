<script setup lang="ts">
import '../assets/main.css'
import IntroComp from './IntroComp.vue'
import AboutComp from './AboutComp.vue'
import ResumeComp from './ResumeComp.vue'
import ProjectsComp from './ProjectsComp.vue'
import ContactComp from './ContactComp.vue'

</script>

<template>
  <main class="main">
    <IntroComp></IntroComp>
    <div class="white_part">
      <AboutComp></AboutComp>
      <ResumeComp></ResumeComp>
      <ProjectsComp></ProjectsComp>
      <ContactComp></ContactComp>
    </div>
  </main>
</template>

<style scoped>
.main {
  background: var(--clr-bg-blue);
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 1.875rem;
}
.white_part {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 100%;
  margin: 0;
  background: var(--clr-bg);
  gap: 3.125rem;
}
</style>
