<template>
  <div class="home">
    <SidebarAccount />
    <p>séparation</p>
    <Profile />
  </div>
</template>

<script>

import SidebarAccount from "@/components/03_organisms/SidebarAccount/SidebarAccount.vue";
import Profile from "@/views/Profile/Profile.vue";

export default {
  name: "Home",
  components: {
    SidebarAccount,
    Profile
  },
  data() {
    return {
      text: "text atom"
    };
  }
};
</script>

<style lang="scss"></style>
