<template>
    <main>
        <MainTopJumboComponent />
        <div class="container">

        </div>
    </main>
</template>
  
  <script>
import MainTopJumboComponent from './MainTopJumboComponent.vue';


  export default {
  name: 'MainComponent',
  components: {
    MainTopJumboComponent,
  }
  }
  </script>
  
  <style lang="scss" scoped>

    @import '../styles/variables.scss';

    main {
        background-color: $bg-dark;
        color: white;
    }
  
  </style>