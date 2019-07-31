<template>
  <div class="col-12 full-width-box text-left" :style="{ backgroundImage: `url(${bgPath})` }">
    <slot></slot>
  </div>
</template>
<script>
export default {
  props: ['bgPath']
}
</script>