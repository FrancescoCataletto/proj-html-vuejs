<template>
  <div>

    <HeaderComponent />
    <JumbotronComponent />
    <MainComponent />
    <FormComponent />
    <FooterComponent />

  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import JumbotronComponent from './components/JumbotronComponent.vue';
import MainComponent from './components/MainComponent.vue';
import FormComponent from './components/FormComponent.vue';
import FooterComponent from './components/FooterComponent.vue';

export default {
    name: "App",
    components: { HeaderComponent, JumbotronComponent, MainComponent, FormComponent, FooterComponent }
}
</script>

<style lang="scss">
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

</style>
