<script setup>
import { ref } from 'vue';
const count = ref(0);
const increment = () =>{
  count.value++;
}

const decrement = () =>{
  count.value--;
}

</script>

<template>
      <div class="wrapper">
        <p>The Number Count Is : {{ count }}</p>
        <button @click="decrement()">Decrement</button>
        <button @click="increment()">Increment</button>
        
      </div>
</template>