<template>
  <router-link to="lala">
    test de link
  </router-link>
</template>

<script>
export default {
  name: 'Link',
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
@import "./Link.scss";
</style>