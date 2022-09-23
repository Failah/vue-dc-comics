<template>
    <div>
        <FooterTopShopComponent/>
    <FooterMiddleLinksComponent/>
    <FooterBottomSocialComponent/>
    </div>
   
</template>
  
  <script>

import FooterTopShopComponent from '@/components/FooterTopShopComponent.vue';
import FooterMiddleLinksComponent from '@/components/FooterMiddleLinksComponent.vue';
import FooterBottomSocialComponent from '@/components/FooterBottomSocialComponent.vue';


  export default {
  name: 'FooterComponent',
  components: {
    FooterBottomSocialComponent,
    FooterMiddleLinksComponent,
    FooterTopShopComponent,
  },
  }
  </script>
  
  <style lang="scss" scoped>
  
  </style>