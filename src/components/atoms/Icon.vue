<template>
  <svg :class="svg.classList">
    <use :xlink:href="`img/icons.svg#${svg.iconRoute}`"></use>
  </svg>
</template>
<script>
export default {
  props: ['svg']
}
</script>
