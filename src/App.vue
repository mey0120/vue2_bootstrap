<template>
  <div id="app">
    <Header />
    <Intro />
    <Section01 />
    <Section02 />
    <Section04 />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Intro from './components/Intro.vue'
import Section01 from './components/Section01.vue'
import Section02 from './components/Section02.vue'
import Section04 from './components/Section04.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Intro,
    Section01,
    Section02,
    Section04,
    Footer
    }
  
}
</script>

<style>
#app{
    margin: 0;
    font-family: Nunito,sans-serif;
    font-size: .813rem;
    font-weight: 400;
    color: #47404f;
    text-align: left;
    background-color: #fff;
}
</style>
