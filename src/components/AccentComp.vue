<script lang="ts">
export default {
  name: 'AccentComp',
  props: { phrase: String }
}
</script>
<template>
  <a class="prop">{{ phrase }}</a>
</template>
<style scoped>
.prop {
  color: var(--clr-txt-accent);
}
</style>
