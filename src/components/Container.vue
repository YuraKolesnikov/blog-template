<template>
  <div class="container">
    <slot></slot>
  </div>
</template>
<script>
export default {
  name: 'Container'
}
</script>
<style lang="scss">
.container {
  max-width: 1180px;
  width: 100%;
  margin: 0 auto;
  padding: 0 30px;
}
</style>