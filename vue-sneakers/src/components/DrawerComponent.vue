<script setup>

import DrawerHead from "@/components/DrawerHead.vue";
import CartItemList from "@/components/CartItemList.vue";
</script>

<template>
  <div class="fixed top-0 left-0 h-full w-full bg-black z-10 opacity-70">
  </div>

  <div class=" bg-white w-96 h-full fixed right-0 top-0 z-20 p-8 mb-6">
    <drawer-head />
    <cart-item-list />

    <div class="flex flex-col gap-4 mt-7">
      <div class="flex gap-2">
        <span>Итого:</span>
        <div class="flex-1 border-b border-dashed"></div>
        <b>12990 Р</b>
      </div>

      <div class="flex gap-2">
        <span>Налог 5%:</span>
        <div class="flex-1 border-b border-dashed"></div>
        <b>12990 Р</b>
      </div>

      <button
          disabled=""
          class="bg-lime-500 w-full rounded-xl py-3 text-white disabled:bg-slate-400 hover:bg-lime-600 transition active:bg-lime-700 cursor-pointer mt-4">Оформить заказ</button>
    </div>


  </div>
</template>

<style scoped>

</style>