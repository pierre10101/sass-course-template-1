<template>
  <div>
    <div class="background">
      <LogoBox styling="background__logo" class="background__logo-box" />
      <CenteredHeading />
    </div>
  </div>
</template>
<script>
import CenteredHeading from "./CenteredHeadingComponent";
import LogoBox from "./LogoBox";
export default {
  name: "Background",
  components: {
    CenteredHeading,
    LogoBox
  },
  props: {
    msg: String
  }
};
</script>
<style scoped lang="scss">
@import "@/assets/sass/abstracts/_mixins";
@import "@/assets/sass/abstracts/_variables";
@import "@/assets/sass/components/_background";
</style>
