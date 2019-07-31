<template>
  <button class="button" :class="button.classList">
    {{button.text}}
  </button>
</template>
<script>
export default {
  props: ['button']
}
</script>
