<template lang="html">
  <div :class="['LoadingLine grow--animation rounded-full bg-grey', width ? width : 'w-16', height ? height : 'h-4']" />
</template>

<script>
export default {
  name: "LoadingLine",
  props: {
    height: {
      default: "",
      type: String
    },
    width: {
      default: "",
      type: String
    }
  }
};
</script>
