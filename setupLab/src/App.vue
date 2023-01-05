<template>
  <div>
    <header/>
<button @click="helloWorld">Click me</button>
  </div>

</template>
<script setup>
import header from './components/header.vue'
setup(){
const helloWorld =()=>{
  return "hellow World"
}
}

</script>

<style scoped>

</style>
