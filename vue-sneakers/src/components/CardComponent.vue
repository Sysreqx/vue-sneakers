<script setup>
  defineProps({
    title: String,
    imageUrl: String,
    price: Number,
    isFavorite: Boolean,
    isAdded: Boolean,
    onClickAdd: Function,
    onClickFavorite: Function
  })
</script>

<template>

  <div class="relative bg-white m-10 border border-slate-100 rounded-xl p-8 cursor-pointer hover:-translate-y-2 hover:shadow-xl transition">
    <img @click="onClickFavorite" :src="!isFavorite ? '/like-1.svg' : '/like-2.svg' " alt="like" class="absolute top-8 left-8">
    <img :src="imageUrl" alt="sneakers">
    <p>Мужские кроссовки Nike Blazer Mid Suede</p>

    <div class="flex justify-between mt-5">
      <div class="flex flex-col">
        <span class="text-slate-400 ">Цена:</span>
        <b>{{ price }}</b>
      </div>

      <img @click="onClickAdd" :src="!isAdded ? '/plus.svg' : '/checked.svg' " alt="plus">
    </div>
  </div>

</template>

<style scoped>

</style>