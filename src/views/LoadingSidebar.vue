<template lang="html">
  <div id="LoadingSidebar" class="flex flex-col justify-between h-screen p-12">
    <header class="flex justify-between mb-8">
      <div class="w-1/2 flex">
        <LoadingThumbnail width="h-8 w-8 mr-4" />
        <LoadingThumbnail width="h-8 w-8" />
      </div>
      <div class="w-1/2 flex justify-between">
        <div class="flex flex-col items-end">
          <LoadingLine class="w-28 mb-4 rounded-lg" />
          <LoadingLine class="w-16 rounded-lg" />
        </div>
        <LoadingThumbnail />
      </div>
    </header>
  </div>
</template>

<script>
import LoadingLine from "../components/loading-components/LoadingLine.vue";
import LoadingThumbnail from "../components/loading-components/LoadingThumbnail.vue";

export default {
  name: "LoadingSidebar",
  components: {
    LoadingThumbnail,
    LoadingLine,
  },
};
</script>
