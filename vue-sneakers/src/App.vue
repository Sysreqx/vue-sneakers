<script setup>
  import HeaderComponent from "@/components/HeaderComponent.vue";
  import CardList from "@/components/CardList.vue";
  import DrawerComponent from "@/components/DrawerComponent.vue";
</script>

<template>
<!--  <drawer-component />-->
  <div class="bg-white w-4/5 m-auto  rounded-xl shadow-xl mt-14">
    <header-component />

    <div class="p-10">
      <div class="flex justify-between items-center">
        <h2 class="text-3xl font-bold ">
          Все кроссовки
        </h2>

        <div class="flex gap-4">
          <select name="" id="" class="py-2 px-3 border rounded-md outline-none">
            <option>По названию</option>
            <option>По цене (дешевые)</option>
            <option>По цене (дорогие)</option>
          </select>

          <div class="relative">
            <img src="/search.svg" alt="searchvsg" class="absolute left-4 top-3">
            <input type="text" placeholder="Поиск..." class="border rounded-md py-2 pl-11 pr-4 outline-none focus:border-gray-400">
          </div>
        </div>
      </div>
    </div>

    <card-list />
  </div>
</template>

<style scoped>

</style>
