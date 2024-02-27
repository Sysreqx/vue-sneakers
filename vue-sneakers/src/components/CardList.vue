<script setup>

import CardComponent from "@/components/CardComponent.vue";

const onClickAdd = () => {
  alert("Add");
}

</script>

<template>
  <div class="p-10">

    <div class="grid grid-cols-2 gap-5">
      <card-component
          title="Мужские Кроссовки Nike Blazer Mid Suede"
          image-url="/sneakers/sneakers-1.jpg"
          :price="5000"
      :is-added="false"
      :is-favorite="true"
      :on-click-add="onClickAdd"/>
    </div>
  </div>
</template>

<style scoped>

</style>