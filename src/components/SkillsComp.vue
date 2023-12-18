<script setup lang="ts">

</script>
<template>
    <div class="skills">
        <h1>Skills</h1>
        <div class="skillset">
          <h2>Frontend</h2>
          <div class="skills_list">
            <a>CSS</a>
            <a>HTML</a>
            <a>Vue.js</a>
            <a>Next.js</a>
            <a>React</a>
            <a>Redux</a>
            <a>Javascript</a>
            <a>Typescript</a>
          </div>
        </div>
        <div class="skillset">
          <h2>Backend</h2>
          <div class="skills_list">
            <a>Express</a>
            <a>Node</a>
            <a>Nest.js</a>
            <a>Next.js</a>
            <a>.NET</a>
            <a>Typescript</a>
            <a>C#</a>
          </div>
        </div>
        <div class="skillset">
          <h2>Database</h2>
          <div class="skills_list">
            <a>MongoDb</a>
          </div>
        </div>
        <div class="skillset">
          <h2>Languages</h2>
          <div class="skills_list">
            <a>Javascript</a>
            <a>Typescript</a>
            <a>C#</a>
            <a>Python</a>
            <a>CSS</a>
            <a>HTML</a>
          </div>
        </div>
        <div class="skillset">
          <h2>Other</h2>
          <div class="skills_list">
            <a>Git</a>
            <a>Github</a>
            <a>Discord</a>
          </div>
        </div>
      </div>
</template>
<style scoped>
.skills {
  display: flex;
  flex-direction: column;
  gap: 0.625rem;
  flex: 1 0 0;
}
.skillset {
  display: flex;
  flex-direction: column;
  gap: 0.625rempx;
}
.skills_list {
  display: flex;
  padding: 0.625rem;
  align-items: flex-start;
  align-content: flex-start;
  gap: 0.625rem;
  align-self: stretch;
  flex-wrap: wrap;
}
.skills_list a {
  font-size: 14px;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
  color: var(--clr-txt-third);
}
.skills h1 {
  margin: 0;
  font-size: 32px;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
  color: var(--clr-txt-accent-2);
}
.skills h2 {
  color: var(--clr-txt-third);
  margin: 0;
  font-size: 24px;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
}
</style>