<script lang="ts">
import '../assets/main.css'
export default {
  name: 'ResumeComp'
}
</script>
<template>
  <div class="resume">
    <h1>Resume</h1>
    <h2>Timeline :</h2>

    <div class="timeline">
      <div class="timeline_work"></div>
      <div class="white_line"></div>
      <div class="years">
        <a>2015</a>
        <a>2016</a>
        <a>2017</a>
        <a>2018</a>
        <a>2019</a>
        <a>2020</a>
        <a>2021</a>
        <a>2022</a>
        <a>2023</a>
      </div>
    </div>

    <h2>Work experience</h2>

    <div class="work">
      <div class="work_history"></div>
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
    </div>
  </div>
</template>
<style scoped>
.resume {
  background: var(--clr-bg);
  display: flex;
  padding: 0.625rem 10.188rem;
  flex-direction: column;
  align-items: flex-start;
  gap: 2.5rem;
  align-self: stretch;
}
.resume h1 {
  margin: 0;
  color: var(--clr-txt-accent-2);
  font-size: 40px;
  font-style: normal;
  font-weight: 600;
  line-height: normal;
}
.resume h2 {
  margin: 0;
  color: var(--clr-txt-third);
  font-size: 32px;
  font-style: normal;
  font-weight: 600;
  line-height: normal;
}
.timeline {
  display: flex;
  height: 21rem;
  padding:  1.875rem;
  flex-direction: column;
  align-items: center;
  gap: 0.625rem;
  align-self: stretch;
  border-radius: 5px;
  background: var(--clr-bg-blue);
}
.work {
  display: flex;
  gap: 2.5rem;
  height: 40rem;
  width: 100%;
}
.work_history {
  display: flex;
  width: 49.5rem;
  padding: 1.563rem;
  flex-direction: column;
  gap: 0.625rem;
  border-radius: 0.625rem;
  background: var(--clr-bg-blue);
}
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
.timeline_work {
  display: flex;
  align-items: center;
  gap: 0.625rem;
  flex: 1 0 0;
  align-self: stretch;
}
.white_line {
  display: flex;
  width: 100%;
  height: 5px;
  background: var(--clr-bg);
}
.years {
  display: flex;
  height: 1.938rem;
  justify-content: space-between;
  align-items: center;
  flex-shrink: 0;
  align-self: stretch;
}
.years a {
  font-size: 20px;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
  color: var(--clr-bg);
}
</style>
