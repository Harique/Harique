<script setup lang="ts">
import HeaderComp from './components/HeaderComp.vue'
import MainComp from './components/MainComp.vue';
import FooterComp from './components/FooterComp.vue';

</script>

<template>
  <div class="main_div">
    <HeaderComp />
    <MainComp />
    <MainComp />
    
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
