<script lang="ts" setup>
import navHead from './components/navHead.vue'
import cardList from './components/cardList.vue'
import drawer from './components/drawer.vue'
</script>

<template>
<!-- <drawer/> -->
<div class="wrapper">
  <navHead/>

  <div class="container">
    <div class="flex justify-between">
      <h2 class="title-grid">Все кроссовки</h2>
      <cardList/>
      <div class=""></div>
    </div>
  </div>
</div>


</template>


