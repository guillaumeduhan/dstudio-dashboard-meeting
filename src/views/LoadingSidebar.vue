<template>
  <div id="LoadingSidebar" class="flex flex-col justify-between h-screen p-12">
    <header class="flex justify-between mb-24">
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
    <div class="Calendar flex flex-col">
      <div class="w-full flex">
        <div class="w-1/2 flex justify-between">
          <LoadingLine class="w-40 h-8 mb-4 rounded-big" />
        </div>
        <div class="w-1/2 flex justify-end">
          <LoadingThumbnail width="h-8 w-8 mr-4" />
          <LoadingThumbnail width="h-8 w-8" />
        </div>
      </div>
      <LoadingLine class="w-full h-56 mb-4 rounded-big" />
    </div>
    <div class="w-full h-full">
      <LoadingLine class="w-full h-full mb-4 rounded-big" />
    </div>
  </div>
</template>

<script>
import LoadingLine from "../components/loading-components/LoadingLine.vue";
import LoadingThumbnail from "../components/loading-components/LoadingThumbnail.vue";

export default {
  name: "LoadingSidebar",
  components: {
    LoadingThumbnail,
    LoadingLine
  }
};
</script>
