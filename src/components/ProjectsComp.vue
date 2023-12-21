<script setup lang="ts">

</script>
<template>
  <div class="container" id="projects">
    <h1>Projects</h1>
    <div class="projects">
      <div class="project"></div>
      <div class="project"></div>
      <div class="project"></div>
      <div class="project"></div>
      <div class="project"></div>
      <div class="project"></div>
    </div>
  </div>
</template>
<style scoped>
.container {
  display: flex;
  padding: 0.625rem 10.188rem;
  flex-direction: column;
  justify-content: center;
  gap: 1.25rem;
}
.container h1 {
  margin: 0;
  font-size: 40px;
  font-style: normal;
  font-weight: 600;
  line-height: normal;
  color: var(--clr-txt-accent-2);
}
.projects {
  display: flex;
  align-items: center;
  align-content: center;
  gap: 1.875rem;
  align-self: stretch;
  flex-wrap: wrap;
}
.project {
  width: 397px;
  height: 254px;
  border-radius: 10px;
  background: #d9d9d9;
}
</style>
