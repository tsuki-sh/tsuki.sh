<script setup lang="ts">
useHead({
  title: 'Tsuki',
});
</script>

<template>
  <main h-full w-full flex="~ col center">
    <TheTsuki />
  </main>
</template>

<style>
html,
body,
#__nuxt {
  height: 100dvh;
  margin: 0;
  padding: 0;
}

html {
  background: black;
  color: white;
}

::selection,
::-moz-selection {
  background-color: white;
  color: black;
}
</style>
