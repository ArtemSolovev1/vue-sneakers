<script setup>
import Card from './Card.vue'

defineProps({
  items: Array
})

const onClickAdd = () => {
  alert('Добавлено')
}
</script>

<template>
  <div class="grid grid-cols-4 gap-5">
    <Card
      v-for="item in items"
      :id="item.id"
      :key="item.id"
      :title="item.title"
      :image-url="item.imageUrl"
      :price="item.price"
      :on-click-add="onClickAdd"
      :is-favorite="item.isFavorite"
    />
  </div>
</template>
