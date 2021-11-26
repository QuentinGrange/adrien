<template>
  <div class="text">
    {{text}}
    <slot name="one"></slot>
    <slot name="two"></slot>
  </div>
</template>

<script>
export default {
  name: "HFText",

  props : {
    text : String,
  },

}
</script>

<style scoped>

</style>