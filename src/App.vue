<script setup lang="ts">
import HeaderComp from './components/HeaderComp.vue'
import MainComp from './components/MainComp.vue'
import FooterComp from './components/FooterComp.vue'

</script>

<template>
  <div class="main_div">
    <header>
      <HeaderComp></HeaderComp>
    </header>
    <MainComp />
    <FooterComp></FooterComp>
  </div>
</template>

<style scoped>
.main_div {
  width: 100%;
  height: 100%;
  display: flex;
  scroll-behavior: smooth;
  overflow-y: scroll;
  flex-direction: column;
  -ms-overflow-style: none;  /* IE and Edge */
  scrollbar-width: none;  /* Firefox */
  scroll-padding: 5rem;
}
.main_div::-webkit-scrollbar {
  display: none;
}
</style>
