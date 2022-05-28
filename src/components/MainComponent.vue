<template>
  <main>
      <OverviewComponent />
      <DiscoverNowComponent />
      <PlanCostComponent />
      <YouTubeComponent />
      <UpcomingEventsComponent />
      <FeedbacksComponent />
  </main>
</template>

<script>
import OverviewComponent from './OverviewComponent.vue';
import DiscoverNowComponent from './DiscoverNowComponent.vue';
import PlanCostComponent from './PlanCostComponent.vue';
import YouTubeComponent from './YouTubeComponent.vue';
import UpcomingEventsComponent from './UpcomingEventsComponent.vue';
import FeedbacksComponent from './FeedbacksComponent.vue';
export default {
    name: "MainComponent",
    components: { OverviewComponent, DiscoverNowComponent, PlanCostComponent, YouTubeComponent, UpcomingEventsComponent, FeedbacksComponent }
}
</script>

<style lang="scss" scoped>

</style>