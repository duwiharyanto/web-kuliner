<template>
  <div id="app">
    <router-view/>
    <FooterVue></FooterVue>
  </div>
</template>
<script>
import FooterVue from './components/Footer.vue'
export default {
  name:'App',
  components:{
    FooterVue
  }
}
</script>
