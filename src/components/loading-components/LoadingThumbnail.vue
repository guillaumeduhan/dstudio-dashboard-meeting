<template lang="html">
  <div class="LoadingThumbnail grow--animation h-16 w-16 rounded-full bg-grey" />
</template>

<script>
export default {
  name: "LoadingThumbnail",
  props: {
    imageUrl: {
      default: "",
      type: String
    }
  }
};
</script>
