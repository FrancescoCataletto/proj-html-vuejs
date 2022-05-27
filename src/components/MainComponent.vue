<template>
  <main>
      <OverviewComponent />
      <DiscoverNowComponent />
      <PlanCostComponent />
      <YouTubeComponent />
  </main>
</template>

<script>
import OverviewComponent from './OverviewComponent.vue';
import DiscoverNowComponent from './DiscoverNowComponent.vue';
import PlanCostComponent from './PlanCostComponent.vue';
import YouTubeComponent from './YouTubeComponent.vue';
export default {
    name: "MainComponent",
    components: { OverviewComponent, DiscoverNowComponent, PlanCostComponent, YouTubeComponent }
}
</script>

<style lang="scss" scoped>

</style>