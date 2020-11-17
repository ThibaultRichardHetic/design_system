<template>
  <div class="home">
    <SidebarAccount />
  </div>
</template>

<script>

import SidebarAccount from "@/components/03_organisms/SidebarAccount/SidebarAccount.vue";

export default {
  name: "Home",
  components: {
    SidebarAccount
  },
  data() {
    return {
      text: "text atom"
    };
  }
};
</script>

<style lang="scss"></style>
