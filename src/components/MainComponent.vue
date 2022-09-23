<template>
  <main>
    <MainTopJumboComponent />
    <MainBottomSeriesComponent />
  </main>
</template>
  
  <script>
import MainTopJumboComponent from "./MainTopJumboComponent.vue";
import MainBottomSeriesComponent from "./MainBottomSeriesComponent.vue";

export default {
  name: "MainComponent",
  components: {
    MainTopJumboComponent,
    MainBottomSeriesComponent,
  },
};
</script>
  
  <style lang="scss" scoped>
@import "../styles/variables.scss";

main {
  background-color: $bg-dark;
  color: white;
}
</style>