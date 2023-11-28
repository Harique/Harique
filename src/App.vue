<script setup lang="ts">
import HeaderComp from './components/HeaderComp.vue'
import IntroComp from './components/IntroComp.vue'
import FooterComp from './components/FooterComp.vue';
</script>

<template>
  <div class="main_div">
    <HeaderComp />
    <IntroComp></IntroComp>
    <FooterComp></FooterComp>
  </div>
</template>

<style scoped>
.main_div{
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
}
</style>
