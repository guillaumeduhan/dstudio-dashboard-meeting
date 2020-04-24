<template lang="html">
  <div
    :class="[
      'LoadingThumbnail grow--animation rounded-full bg-grey',
      width ? width : 'h-16 w-16',
    ]"
  />
</template>

<script>
export default {
  name: "LoadingThumbnail",
  props: {
    height: {
      default: "",
      type: String,
    },
    width: {
      default: "",
      type: String,
    },
  },
};
</script>
