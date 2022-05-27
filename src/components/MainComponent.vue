<template>
  <main>
      <OverviewComponent />
      <DiscoverNowComponent />
      <PlanCostComponent />
  </main>
</template>

<script>
import OverviewComponent from './OverviewComponent.vue';
import DiscoverNowComponent from './DiscoverNowComponent.vue';
import PlanCostComponent from './PlanCostComponent.vue';
export default {
    name: "MainComponent",
    components: { OverviewComponent, DiscoverNowComponent, PlanCostComponent }
}
</script>

<style lang="scss" scoped>

</style>