<template lang="html">
  <div id="LoadingDashboard">
    <header class="flex items-center justify-between h- p-10">
      <div class="w-1/4">
        <LoadingThumbnail />
      </div>
      <div class="w-3/4 flex items-center justify-between">
        <LoadingLine width="w-full mx-2" height="h-8" />
        <LoadingLine width="w-64" height="h-10" />
      </div>
    </header>
    <div>
      
    </div>
  </div>
</template>

<script>
import LoadingLine from "../components/loading-components/LoadingLine.vue";
import LoadingThumbnail from "../components/loading-components/LoadingThumbnail.vue";

export default {
  name: "LoadingDashboard",
  components: {
    LoadingThumbnail,
    LoadingLine
  }
};
</script>
