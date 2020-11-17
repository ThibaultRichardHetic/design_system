<template>
  <router-link to="/">
    <slot />
  </router-link>
</template>

<script>
export default {
  name: 'CpLink',
  props: ['to'],
}
</script>


<style lang="scss">
@import "./CpLink.scss";
</style>