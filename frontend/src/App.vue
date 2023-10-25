<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
    <a href="https://wails.io/" target="_blank">
      <img src="./assets/wails.png" class="logo wails" alt="Wails logo" />
    </a>
    <a href="https://www.typescriptlang.org/" target="_blank">
      <img src="./assets/typescript.svg" class="logo typescript" alt="Typescript logo" />
    </a>
    <a href="https://www.naiveui.com/" target="_blank">
      <img src="./assets/naive-ui.svg" class="logo naive-ui" alt="Naive-ui logo" />
    </a>
    <a href="https://pinia.vuejs.org/" target="_blank">
      <img src="./assets/pinia.svg" class="logo pinia" alt="Pinia logo" />
    </a>
  </div>
  <HelloWorld msg="Wails + Vite + Vue + TypeScript + NaiveUI + Pinia" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
.logo.wails:hover {
  filter: drop-shadow(0 0 2em #D02A2C);
}
.logo.typescript:hover {
  filter: drop-shadow(0 0 2em #1296DB);
}
.logo.naive-ui:hover {
  filter: drop-shadow(0 0 2em #5FBC21);
}
.logo.pinia:hover {
  filter: drop-shadow(0 0 2em #FFCF48);
}
</style>
