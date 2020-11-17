<template>
  <div class="home">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <SpText tag="p">{{ text }}</SpText>
    <Separator/>
    <Input/>
    <Input type="checkbox"/>
    <Link/>
    <Avatar/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import SpText from "@/components/01_atoms/SpText/SpText.vue";
import Separator from "@/components/01_atoms/Separator/Separator.vue";
import Input from "@/components/01_atoms/Input/Input.vue";
import Link from "@/components/01_atoms/Link/Link.vue";
import Avatar from "@/components/01_atoms/Avatar/Avatar.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
    SpText,
    Separator,
    Input,
    Link,
    Avatar
  },
  data() {
    return {
      text: "text atom"
    };
  }
};
</script>

<style lang="scss"></style>
