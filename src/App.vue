<template>

  <body id="app">
       <HeaderFlow/>
      <section class="flow-container">
        <div class="flow-row">
          <MobileMenu/>
          <Hero/>
          <Products/>
          </div>
        </section>
       <FooterFlow/>
  </body>
</template>


<script>
import Vue from 'vue'
import Hero from './components/Hero.vue'
import Products from './components/Products.vue'
import HeaderFlow from './components/HeaderFlow.vue'
import FooterFlow from './components/FooterFlow.vue'
import MobileMenu from './components/MobileMenu.vue'
/* Bootstrap load */
import { BootstrapVue, IconsPlugin } from 'bootstrap-vue'
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'


// Make BootstrapVue available throughout your project
Vue.use(BootstrapVue)
// Optionally install the BootstrapVue icon components plugin
Vue.use(IconsPlugin)



require('@/assets/css/styles.scss') 
export default {
  name: 'App',
  components: {
     HeaderFlow,
     FooterFlow,
     Hero,
     Products,
     MobileMenu


     
    }
   
  }



</script>


