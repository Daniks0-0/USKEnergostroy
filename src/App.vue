<script setup>
// import HelloWorld from './components/HelloWorld.vue'
// import TheWelcome from './components/TheWelcome.vue'
import Main from './components/Main.vue'

import '../src/assets/base.css'
</script>

<template>

  <header>
   
  </header>
  <main>
    <Main> </Main>
  </main>

  
</template>

<style scoped lang="scss">
main {
  h1 {
    font-size: var(--s); // Используем переменную --s
    color: var(--color-text); // Используем переменную --color-text
    background-color: var(--vt-c-white); // Используем переменную --vt-c-white
  }
}
</style>