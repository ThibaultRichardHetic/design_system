<template>
  <div>
    <input type="checkbox" v-model="checked">
    <label>{{ checked }}</label>
  </div>
</template>

<script>

export default {
  name: "CpSwitch",
  data() {
    return {
      checked: "true",
      Mode: "DarkMode"
    };
  }
};
</script>

<style lang="scss">
@import "CpSwitch.scss";
</style>

