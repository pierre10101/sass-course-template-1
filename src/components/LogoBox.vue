<template>
  <img :src="image" alt="Logo" :class="styling" />
</template>
<script>
export default {
  props: {
    image: {
      type: String,
      default: require("../assets/img/logo-white.png")
    },
    styling: {
      type: String,
      required: true
    }
  }
};
</script>
