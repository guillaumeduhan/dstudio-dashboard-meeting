<template lang="html">
  <div class="Thumbnail h-24 w-24" />
</template>

<script>
export default {
  name: "Thumbnail",
  props: {
    imageUrl: {
      default: "",
      type: String
    }
  }
};
</script>
