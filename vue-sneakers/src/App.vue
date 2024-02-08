<script setup>
  import MyComponent from "@/components/MyComponent.vue";
  import CompositionComponent from "@/components/CompositionComponent.vue";
</script>

<template>
  <div class="bg-white w-4/5 m-auto h-screen rounded-xl shadow-xl mt-14">

    <header class="flex justify-between border-b border-slate-300 px-8 py-8">
      <div class="flex items-center gap-4">
        <img src=" /logo.png" alt="logo" class="w-10">

        <div>
          <h2 class="text-xl font-bold uppercase">Vue skeankers</h2>
          <p class="text-slate-400">Магазин лучших кроссовок</p>
        </div>
      </div>

      <ul class="flex items-center gap-10">
        <li class="flex items-center gap-3"><img src="/cart.svg" alt="cart"><b>1205 тенге</b></li>
        <li class="flex items-center gap-3"><img src="/heart.svg" alt="heart"><b>Закладки</b></li>
        <li class="flex items-center gap-3"><img src="/profile.svg" alt="profile"><b>Профиль</b></li>
      </ul>
    </header>
  </div>
</template>

<style scoped>

</style>
