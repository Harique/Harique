<script lang="ts">
import '../assets/main.css'
export default {
  name: 'AboutComp'
}
</script>

<template>
  <div class="about">
    <div class="image">
      <img src="../assets/Laptop.jpg" alt="laptop" />
    </div>
    <div class="writing">
      <h1>Background</h1>
      <p>
        my name is Hakim Oukil and i am a self-taught software engineer, i define myself as a
        passionate technology guy who likes to try new things and take on harder challenges to
        improve and adapt to the situation whenever needed, i am more of a software focused
        developer with a strong grasp on server side technologies such as: APIs, databases using
        languages such as : C#, JS/TS, Java and more.
      </p>
    </div>
  </div>
</template>

<style scoped>
.about {
  display: flex;
  height: 41rem;
  padding: 0.625rem 9.75rem 0.625rem 10.188rem;
  justify-content: center;
  align-items: center;
  gap: 1rem;
  align-self: stretch;
}
.image {
  display: flex;
  width: 507px;
  height: 354px;
}
.image img {
  display: flex;
  height: 22rem;
  width: 28rem;
  border-radius: 10px;
}
.writing {
  display: flex;
  width: 29.75rem;
  height: 23rem;
  padding: 0.625rem 0px;
  flex-direction: column;
  align-items: flex-start;
  gap: 0.625rem;
}
.writing h1 {
  padding: 0.625rem 0;
  margin: 0;
  color: var(--clr-txt-accent-2);
  font-size: 24px;
  font-style: normal;
  font-weight: 600;
  line-height: normal;
}
.writing p {
  color: var(--clr-txt-secondary);
  margin: 0;
  font-size: 20px;
  font-style: normal;
  font-weight: 400;
  line-height: 155.827%; /* 31.165px */
}
</style>
