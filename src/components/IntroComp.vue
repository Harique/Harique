<script lang="ts">
import '../assets/main.css'
export default {
  name: 'IntroComp'
}
</script>

<template>
  <main class="main">
    <div class="intro">
      <h1>HI! I’m <a>Hakim</a> oukil</h1>
      <p>
        I’m a self-taught <a>software engineer</a> with a strong foundation in
        <a>web-development</a>. I’m passionate about <a>web-development</a>,<a>software</a>, and
        everything related to Technology.
      </p>
      <div class="button">
        <p>My Projects</p>
      </div>
    </div>
  </main>
</template>
<style scoped>
.main {
  display: flex;
  width: 100%;
  height: 100%;
  padding: 10.625rem 5rem;
  gap: 0.625rem;
  flex: 1 0 0;
  flex-direction: column;
  align-items: flex-start;
  align-self: stretch;
}
.intro {
  display: flex;
  width: 47.5rem;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  gap: 1.25rem;
  padding: 0.938rem 0;
}
.button {
  display: flex;
  width: 11.5rem;
  height: 3.75rem;
  justify-content: center;
  align-items: center;
  gap: 0.625rem;
  border-radius: 5px;
  border: 1px solid var(--clr-txt-accent);
  background: var(--clr-txt-accent);
}
.button p {
    color: var(--clr-bg);
    font-size: 20px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
}
.intro h1 {
  color: var(--clr-txt-primary);
  height: min-content;
  font-size: 48px;
  font-weight: 400;
  line-height: normal;
  margin: 0;
}
h1 a {
  color: var(--clr-txt-accent);
}
p {
  color: var(--clr-txt-secondary);
  font-size: 20px;
  margin: 0;
}
p a {
  color: var(--clr-txt-primary);
}
</style>
