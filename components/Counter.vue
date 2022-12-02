<template>
    <div>
      Hello, world
      <button @click="incriment">Incr</button>
      <p>{{count}}</p>
      <button @click="decriment">Decr</button>
    </div>
  </template>
  
  <script setup>
  const count = ref(0);
  
  function incriment(){
    count.value++
  }
  function decriment(){
    count.value--
  }
  </script>