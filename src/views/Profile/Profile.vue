<template>
  <main class="main--profile">
    <CpText tag="h1" type="title">{{ h1 }}</CpText>
    <CpForm/>
    <CpArticle/>
    <ButtonText type="destructive" :content="textButton"/>
  </main>
</template>

<script>
import CpText from "@/components/01_atoms/CpText/CpText.vue";
import CpForm from "@/components/03_organisms/CpForm/CpForm.vue";
import CpArticle from "@/components/02_molecules/CpArticle/CpArticle.vue";
import ButtonText from "@/components/02_molecules/ButtonText/ButtonText.vue";

export default {
  name: "Profile",
  components: {
    CpText,
    CpForm,
    CpArticle,
    ButtonText
  },
  data() {
    return {
      h1: "Profile",
      textButton: "Delete my account"
    };
  }
};
</script>

<style lang="scss">
@import "./Profile.scss";
</style>
