<template>
  <div class="colortheme">
    <CpSwitch />
    <CpText tag="p">{{ Mode }}</CpText>
  </div>
</template>

<script>
import CpSwitch from "@/components/01_atoms/CpSwitch/CpSwitch.vue";
import CpText from "@/components/01_atoms/CpText/CpText.vue";

export default {
  name: "ColorTheme",
  components: {
    CpSwitch,
    CpText
  },
  data() {
    return {
      Mode: "DarkMode"
    };
  }
};
</script>

<style lang="scss">
@import "ColorTheme.scss";
</style>

