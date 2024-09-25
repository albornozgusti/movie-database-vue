<template>
  <div class="d-flex flex-column bg-body text-body">
    <headerItem />
    <searchContainer class="px-4 py-4" />
    <div>results</div>
    <div>footer</div>
  </div>
</template>

<script setup>
import headerItem from './components/header/headerItem.vue'
import searchContainer from './components/searchContainer/searchContainer.vue'
</script>
