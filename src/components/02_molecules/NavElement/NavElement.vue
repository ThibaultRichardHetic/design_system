<template>
  <div>
    <CpLink :to="elText">{{ elText }}</CpLink>
  </div>
</template>

<script>
import CpLink from "@/components/01_atoms/CpLink/CpLink.vue";

export default {
  name: "NavElement",
  components: {
    CpLink
  },
  props: ['elText'],
};
</script>

<style lang="scss">
@import "NavElement.scss";
</style>

