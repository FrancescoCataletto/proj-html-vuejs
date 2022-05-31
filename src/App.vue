<template>
  <div>

    <HeaderComponent :lingua ="lingua"
                     :navArr ="navArr"/>
    <JumbotronComponent />
    <MainComponent />
    <FormComponent />
    <FooterComponent :rightExploreArr = "rightExploreArr"
                     :leftExploreArr = "leftExploreArr"
                     :informationArr = "informationArr"/>

  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import JumbotronComponent from './components/JumbotronComponent.vue';
import MainComponent from './components/MainComponent.vue';
import FormComponent from './components/FormComponent.vue';
import FooterComponent from './components/FooterComponent.vue';

import {lingua} from "./assets/img/HeaderData";
import { navArr } from './assets/img/HeaderData';

import { rightExploreArr } from './assets/FooterData';
import { leftExploreArr } from './assets/FooterData';
import { informationArr } from './assets/FooterData';
export default {
    name: "App",
    components: { HeaderComponent, JumbotronComponent, MainComponent, FormComponent, FooterComponent },
    data(){
      return{
        lingua: lingua,
        navArr: navArr,
        rightExploreArr: rightExploreArr,
        leftExploreArr: leftExploreArr,
        informationArr: informationArr
      }
    }
}
</script>

<style lang="scss">
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}

</style>
