<template lang="html">
  <div id="app" class="flex bg-aqua h-screen overflow-hidden">
    <div class="w-4/6">
      <LoadingDashboard v-if="isLoading" />
    </div>
    <div class="w-2/6 h-screen bg-white">
      <LoadingSideBar v-if="isLoading" />
    </div>
  </div>
</template>

<script>
import LoadingDashboard from "./views/LoadingDashboard.vue";
import LoadingSideBar from "./views/LoadingSidebar.vue";

export default {
  name: "App",
  components: {
    LoadingDashboard,
    LoadingSideBar,
  },
  data() {
    return {
      isLoading: true,
    };
  },
};
</script>
