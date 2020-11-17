<template>
  <component
  :is="tag" :class="`separator--${type}`"
  >
  </component>
</template>



<script>
// changer le nom de la class
// user badge
// un element de la side bar est une molécule 
// organisme
export default {
  name: 'Separator',
  props: {
    tag: {
      type: String,
      default: 'div',
    },
    type: {
      type: String,
      default: 'body-m',
    },
  }
}
</script>


<style lang="scss">
@import "./Separator.scss";
</style>