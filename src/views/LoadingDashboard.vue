<template lang="html">
  <div id="LoadingDashboard" class="h-screen p-12">
    <header class="flex items-center pb-20 justify-between">
      <div class="w-1/4">
        <LoadingThumbnail />
      </div>
      <div class="w-3/4 flex items-center justify-between">
        <LoadingLine class="rounded-full ml-2" width="w-32 mx-2" height="h-4" />
        <LoadingLine class="rounded-full mr-2" width="w-32 mx-2" height="h-4" />
        <LoadingLine class="rounded-full" width="w-72" height="h-10" />
      </div>
    </header>
    <div class="flex justify-between pb-8">
      <LoadingLine class="rounded-full" width="w-64" height="h-8" />
      <LoadingLine class="rounded-full" width="w-24" height="h-8" />
    </div>
    <div class="flex">
      <LoadingLine class="rounded-full mr-2" width="w-32" height="h-4" />
      <LoadingLine class="rounded-full mr-2" width="w-32" height="h-4" />
      <LoadingLine class="rounded-full mr-2" width="w-32" height="h-4" />
      <LoadingLine class="rounded-full mr-2" width="w-32" height="h-4" />
    </div>
    <div class="flex py-8">
      <div class="flex flex-col mr-2 w-1/3">
        <div class="flex w-full mb-4">
          <div class="w-1/2 mr-2">
            <LoadingLine class="rounded-big" width="w-full" height="h-24" />
          </div>
          <div class="w-1/2 ml-2">
            <LoadingLine class="rounded-big" width="w-full" height="h-24" />
          </div>
        </div>
        <div class="w-full">
          <LoadingLine class="rounded-big" width="w-full" height="h-24" />
        </div>
      </div>
      <div class="w-1/3 ml-2 mr-2">
        <LoadingLine class="rounded-big" width="w-full" height="h-52" />
      </div>
      <div class="w-1/3 ml-2">
        <LoadingLine class="rounded-big mb-4" width="w-full" height="h-28" />
        <LoadingLine class="rounded-big mt-4" width="w-full" height="h-20" />
      </div>
    </div>
    <div class="flex justify-between pt-8 pb-6">
      <LoadingLine class="rounded-full" width="w-66" height="h-8" />
      <LoadingLine class="rounded-full" width="w-24" height="h-8" />
    </div>
    <div class="flex justify-between pb-8">
      <div class="w-1/2 mr-2">
        <LoadingLine class="rounded-big" width="w-full" height="h-36" />
      </div>
      <div class="w-1/2 ml-2">
        <LoadingLine class="rounded-big" width="w-full" height="h-36" />
      </div>
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
