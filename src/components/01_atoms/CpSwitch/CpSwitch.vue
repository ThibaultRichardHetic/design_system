<template>
  <div>
    <input type="checkbox" id="switch" />
    <label for="switch">Toggle</label>
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
@import "./CpSwitch.scss";
</style>

