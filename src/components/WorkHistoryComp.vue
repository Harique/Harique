<script setup lang="ts"></script>
<template>
  <div class="container">
    <div class="zeptile">
      <div class="head">
        <div class="role">
          <h3>Zeptile Software Inc.</h3>
          <h4>Junior full-stack engineer, (Remote)</h4>
        </div>
        <div class="time">
          <h4>September 2022 - Present</h4>
        </div>
      </div>
      <p>
        “we make custom fitted software curated to customer needs. We don’t have many restrictions
        in terms of technological expertise, if you can think of it, we can make it.”
      </p>
      <div class="tasks">
        <p>- Set up the company’s website project and finished the overall layout of the site.</p>
        <div class="tech_used">
          <a>Typescript</a>
          <a>React</a>
          <a>Nextjs</a>
          <a>Redux</a>
          <a>CSS</a>
          <a>HTML</a>
          <a>Tailwind</a>
        </div>
        <p>
          - Connected the back-end to the database and set up endpoints and custom types to pass the
          data to the front-end and display them.
        </p>
        <div class="tech_used">
          <a>Typescript</a>
          <a>React</a>
          <a>Nextjs</a>
          <a>MySQL</a>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.container {
  display: flex;
  flex-direction: column;
  width: 100%;
  justify-content: space-between;
  gap: 10px;
}
.head {
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
  width: 100%;
}
.role {
  display: flex;
  flex-direction: column;
  gap: 10px;
}
.role h3 {
  font-size: 20px;
  font-weight: 500;
  color: var(--clr-txt-accent);
}
.role h4 {
  font-size: 16px;
  font-weight: 400;
  color: var(--clr-txt-primary);
}
.time h4 {
  font-size: 16px;
  font-weight: 400;
  color: var(--clr-txt-primary);
}
p {
  color: var(--clr-txt-work-p);
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
}
.zeptile {
  display: flex;
  flex-direction: column;
  gap: 10px;
}
.tasks {
  display: flex;
  padding: 10px 35px;
  flex-direction: column;
  align-items: flex-start;
  align-self: stretch;
}
.tech_used {
  display: flex;
  padding: 5px;
  justify-content: center;
  align-items: center;
  gap: 10px;
}
.tech_used a {
    color: var(--clr-txt-primary);
  font-size: 12px;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
}
</style>
