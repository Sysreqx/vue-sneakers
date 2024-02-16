<script setup>
  import HeaderComponent from "@/components/HeaderComponent.vue";
  import CardList from "@/components/CardList.vue";
  import DrawerComponent from "@/components/DrawerComponent.vue";
</script>

<template>
  <drawer-component />
  <div class="bg-white w-4/5 m-auto  rounded-xl shadow-xl mt-14">
    <header-component />

    <card-list />
  </div>
</template>

<style scoped>

</style>
