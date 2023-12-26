<script setup lang="ts">

</script>
<template>
  <div class="container" id="contact">
    <h1>Let's have a <a>chat !</a></h1>
    <h2><a>loiza2330@gmail.com</a></h2>
    <button class="button">
      <p>Contact me</p>
    </button>
  </div>
</template>
<style scoped>
.container {
  display: flex;
  padding: 5rem;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 1.875rem;
  max-height: min-content;
}
.container h1 {
  color: var(--clr-txt-third);
  margin: 0;
  font-size: 40px;
  font-style: normal;
  font-weight: 600;
  line-height: normal;
}
.container a {
  margin: 0;
  color: var(--clr-txt-accent-2);
}
.container h2 {
  margin: 0;
}
.button {
  display: flex;
  width: 11.5rem;
  height: 3.5rem;
  padding: 0.625rem;
  justify-content: center;
  align-items: center;
  gap: 0.625rem;
  background: var(--clr-txt-accent);
  border: 0;
  border-radius: 5px;
  transition: all 0.2s linear;
}
.button:hover{
  background: var(--clr-bg-blue);
}
.button p {
  color: var(--clr-bg);
  display: flex;
  flex-direction: column;
  justify-content: center;
  text-align: center;
  font-size: 20px;
  font-weight: 600;
}
</style>
