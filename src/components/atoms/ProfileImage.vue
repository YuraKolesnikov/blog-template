<template>
  <img :src="img.src" :alt="img.alt" class="postcard__img">
</template>
<script>
export default {
  props: ['img']
}
</script>