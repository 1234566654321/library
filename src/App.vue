<template>
<body id="app">
  <BankCard></BankCard>
  <Stepper></Stepper>
  <GoodsCard></GoodsCard>>
  <Boutique></Boutique>>
   </body>
</template>

<script>
//  import VueAwesomeSwiper from '../node_modules/vue-awesome-swiper'
   import '../node_modules/swiper/dist/css/swiper.css'
import BankCard from './components/common/BankCard/BankCard.vue'
import Stepper from './components/common/Stepper/Stepper.vue'
import GoodsCard from './components/common/GoodsCard/GoodsCard.vue'
import Boutique from './components/common/Boutique/Boutique.vue'

export default {
  name: 'app',
  components: {
    BankCard,
    Stepper,
    GoodsCard,
    Boutique,
    
  }
}
 </script>
<style  scoped>




#app{
 padding: 0;
 margin:0;
}
</style>

