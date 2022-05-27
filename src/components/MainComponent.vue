<template>
  <main>
      <OverviewComponent />
      <DiscoverNowComponent />
  </main>
</template>

<script>
import OverviewComponent from './OverviewComponent.vue';
import DiscoverNowComponent from './DiscoverNowComponent.vue';
export default {
    name: "MainComponent",
    components: { OverviewComponent, DiscoverNowComponent }
}
</script>

<style lang="scss" scoped>

</style>