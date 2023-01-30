<template>
  <HeaderSection/>
  <MainSection/>
   <CardSection/>
</template>

<script>
import HeaderSection from './components/HeaderSection.vue';
import MainSection from './components/MainSection.vue';
import CardSection from './components/CardSection.vue';
export default {
  name: 'App',
  components: {
    HeaderSection , MainSection, CardSection,
  }
}
</script>


<style lang="scss">
@import "./assets/scss/_var.scss";
@import "./assets/scss/style.scss";
</style>
