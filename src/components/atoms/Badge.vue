<template>
  <span class="badge" :class="badge.classList">
    {{badge.text}}
  </span>
</template>
<script>
export default {
  props: ['badge']
}
</script>
