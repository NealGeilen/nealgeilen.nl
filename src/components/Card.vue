<template>
  <div class="card-container">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'Card'
}
</script>

<style scoped>
.card-container{
  border-radius: 4px;
  padding: 5px 6px;
  background-color: #000;
  color: #fff
}
</style>
