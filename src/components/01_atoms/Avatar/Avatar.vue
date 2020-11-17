<template>
  <div :class="`avatar`">
    <p :class="`avatar--name`">JF</p>
  </div>
</template>

<script>
export default {
  name: 'Avatar',
  props: {
    tag: {
      type: String,
      default: 'p',
    },
    type: {
      type: String,
      default: 'body-m',
    },
  }
}
</script>


<style lang="scss">
@import "./Avatar.scss";
</style>