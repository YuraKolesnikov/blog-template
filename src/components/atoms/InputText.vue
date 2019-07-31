<template>
  <div>
    <input 
      :name="input.id" 
      :id="input.id" 
      :type="input.type"
      :placeholder="input.placeholder"
      :required="input.required" 
      v-model="input.vModel"
      class="input input--text" />
  </div>
</template>
<script>
/* Can accept text/password/number/other text formats */
export default {
  props: ['input']
}
</script>