<template>
  <div id="app">
    <navbar/>
    <Header/>
    <servicess/>
    <vclass/>
    <testimonies/>
    <apply/>
    <footers/>
  </div>
</template>

<script>
import navbar from './components/navbar.vue'
import Header from './components/Header.vue'
import servicess from './components/servicess.vue'
import Vclass from './components/vclass.vue'
import testimonies from './components/testimonies.vue'
import apply from './components/apply.vue'
import footers from './components/footers.vue'

export default {
  name: 'App',
  components: {
     navbar, Header, servicess,
    Vclass, testimonies, apply, footers
  }
}
</script>


