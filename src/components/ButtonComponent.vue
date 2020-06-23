<template>
  <a href="#" :class="colour + ' ' + animate" class="btn">Discover Our Tours</a>
</template>
<script>
export default {
  name: "ButtonComponent",
  props: {
    colour: {
      type: String,
      required: true,
    },
    animate: {
      type: String,
      required: false,
    },
  },
};
</script>
