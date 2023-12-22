<script setup lang="ts">
import '../assets/main.css'
import GithubIcon from './icons/IconGithub.vue'
import LinkedInIcon from './icons/IconLinkedIn.vue'
import AccentComp from './AccentComp.vue'


</script>

<template>
  <div class="intro">
    <div class="writing">
      <h2>Hi, my name is:</h2>
      <h1><AccentComp phrase="Hakim" /> Oukil</h1>
      <p>
        I’m a self-taught software engineer with a strong foundation in
        <AccentComp phrase="web-development" />,<br />
        <AccentComp phrase="automation" />, <AccentComp phrase="software development" />, and
        everything in between.
      </p>
      <div class="icons">
        <GithubIcon></GithubIcon>
        <LinkedInIcon></LinkedInIcon>
      </div>
      <div class="button">
        <p>My Projects</p>
      </div>
    </div>
  </div>
</template>
<style scoped>
.intro {
  display: flex;
  padding: 7.813rem 15.938rem;
  height: 26.25rem;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 0.625rem;
  flex-shrink: 0;
  align-self: stretch;
}
.writing {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 0.938rem;
  flex: 1 0 0;
  align-self: stretch;
  margin: 0;
}
.icons {
  display: flex;
  padding: 0.625rem;
  align-items: flex-start;
  gap: 0.625rem;
}
h2 {
  margin: 0;
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  color: var(--clr-txt-primary);
  height: min-content;
}
h1 {
  margin: 0;
  font-size: 64px;
  font-style: normal;
  font-weight: 600;
  line-height: normal;
  color: var(--clr-txt-primary);
}
p {
  margin: 0;
  font-size: 20px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  color: var(--clr-txt-primary);
}
.button {
  display: flex;
  width: 10.25rem;
  height: 2.5rem;
  padding: 0.625rem;
  justify-content: center;
  text-align: center;
  align-items: flex-start;
  gap: 0.625rem;
  border-radius: 5px;
  background: var(--clr-txt-accent);
}
.button p {
  color: var(--clr-bg-darker-blue);
  display: flex;
  flex-direction: column;
  justify-content: center;
  flex: 1 0 0;
  align-self: stretch;
  font-size: 20px;
  font-weight: 500;
}
</style>
