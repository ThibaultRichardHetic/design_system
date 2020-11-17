<template>
    <input :type="`${type}`" :placeholder="`${placeholder}`">
</template>


<script>
// changer le nom de la class
export default {
  name: 'Input',
  props: {
    tag: {
      type: String,
      default: 'div',
    },
    type: {
      type: String,
      default: 'text',
    },
    placeholder: {
      type: String,
      default: 'testplaceholder'
    },
  }
}
</script>


<style lang="scss">
@import "./Input.scss";
</style>