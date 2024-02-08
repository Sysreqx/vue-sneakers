<script setup>
  import {ref} from "vue";

  let count = ref(0);

  defineProps({
    title: String,
    price: Number
  })

  function increment() {
    count.value++;
    console.log(count);
  }

  function updateCount(event) {
    count.value = event.target.value;
  }

</script>

<template>
<!--  <p>{{ count }}</p>-->
<!--  <button @click="increment">+</button>-->
<!--  <input @input="updateCount" />-->

  <div class="product">
    <h2>Товар: {{ title }}</h2>
    <h2>Цена: {{ price }}</h2>
  </div>
</template>

<style scoped>

</style>