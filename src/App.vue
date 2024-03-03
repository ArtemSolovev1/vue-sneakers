<script setup>
import Header from './components/Header.vue'
import CardList from './components/CardList.vue'
</script>

<template>
  <div class="bg-white w-4/5 mx-auto rounded-xl shadow-xl mt-14">
    <Header />

    <div class="p-10">
      <h2 class="text-3xl font-bold mb-10">Все кроссовки</h2>

      <CardList />
    </div>
  </div>
</template>

<style></style>
