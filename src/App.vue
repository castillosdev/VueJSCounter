<script setup>
  import { ref } from 'vue';
  const counter = ref(0);
</script>

<template>
        <div class="counter">
          <div class="counterContent">
              <h2>The current count is...</h2>
              <h1>{{ counter }}</h1>
              <button @click="counter++">+</button>
              <button @click="counter--">-</button>
          </div>
        </div>
</template>

<style scoped>
.counter{
    text-align: center;
    width: 100vw;
    height: 100vh;
    background-color: aliceblue;
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>
