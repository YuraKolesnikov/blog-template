<template>
  <input 
    :id="input.id"
    type="checkbox" 
    :name="input.name"
    v-model="input.vModel" />
</template>
<script>
export default {
  props: ['input']
}
</script>