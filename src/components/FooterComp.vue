<script setup lang="ts">

</script>
<template>
  <footer class="footer">
    <div class="copyright"><p>Copyright © 2023. All rights reserved</p></div>
    <div class="credits">
      <h1>Credits:</h1>
      <a>Stefan Topalovic</a>
      <a>Andrew Lu</a>
      <a>Stormix</a>
    </div>
  </footer>
</template>
<style scoped>
.footer {
  display: flex;
  min-height:fit-content;
  padding: 0.625rem 10.188rem;
  justify-content: space-between;
  flex: 1 0 0;
  background: var(--clr-bg-darker-blue);
}
.copyright {
  display: flex;
  width: 21.5rem;
  padding: 0.625rem;
  justify-content: center;
  align-items: center;
  gap: 0.625rem;
}
.copyright p {
  margin: 0;
  color: var(--clr-bg);
  font-size: 20px;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
}
.credits {
  display: flex;
  width: 12.313rem;
  padding: 0.625rem 0px;
  flex-direction: column;
  gap: 0.938rem;
}
.credits h1 {
  margin: 0;
  font-size: 20px;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
  color: var(--clr-bg);
}
.credits a {
  color: #bebebe;
  margin: 0;
  font-size: 16px;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
}
</style>
