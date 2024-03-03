<script setup>
import Card from './Card.vue'

const onClickAdd = () => {
  alert('Добавлено')
}
</script>

<template>
  <div class="grid grid-cols-4 gap-5">
    <Card
      image-url="/sneakers/sneakers-1.jpg"
      title="Мужские кроссовки Nike Blazer Mid Suede"
      :price="1200"
      :is-added="true"
      :is-favorite="true"
      :on-click-add="onClickAdd"
    />
  </div>
</template>
