<template>
  <router-link :to="navLink.to" class="navbar__link">
    {{navLink.text}}
  </router-link>
</template>
<script>
export default {
  props: ['navLink']
}
</script>