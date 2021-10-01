<template>
<header class="header">
  <b-navbar type="dark" toggleable="lg">
    <div class="container">

      <b-navbar-brand href="#intro-wrap">SJ</b-navbar-brand>
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav class="nav justify-content-end">
        <b-navbar-nav class="ml-auto">
          <b-nav-item href="#intro-wrap">Home </b-nav-item>
          <b-nav-item href="#section01-wrap">Icons</b-nav-item>
          <b-nav-item href="#section02-wrap">Services</b-nav-item>
          <b-nav-item href="#section04-wrap">Contact Us</b-nav-item>

        </b-navbar-nav>
      </b-collapse>
    </div>
  </b-navbar>
</header>
</template>

<script>
export default {
  name: 'Header',

  mounted() {
    window.addEventListener("scroll", this.callbackFunc);
  },
  methods: {
    callbackFunc() {
      const y = window.pageYOffset;
      if (y > 100) {
        document.querySelector("header").classList.add("on");
      } else {
        document.querySelector("header").classList.remove("on");
      }
    }
  }
}
</script>

<style scoped>
header{
  position: fixed;
    width: 100%;
    -webkit-box-shadow: none;
    box-shadow: none;
    top: 0;
    left: 0;
    right: 0;
    padding: 22px 0;
    transition: all .5s ease-in-out;
    -webkit-transition: all .5s ease-in-out;
    z-index: 999;
    background: transparent;
}
header.on{
  position: fixed!important;
    left: 0;
    right: 0;
    top: 0;
    padding: 0!important;
    -webkit-box-shadow: 0 0 4px rgb(0 0 0 / 14%), 0 4px 8px rgb(0 0 0 / 28%);
    box-shadow: 0 0 4px rgb(0 0 0 / 14%), 0 4px 8px rgb(0 0 0 / 28%);
    -webkit-animation: slideDown .6s forwards;
    animation: slideDown .6s forwards;
    -webkit-transition: all .5s ease-in-out!important;
    transition: all .5s ease-in-out!important;
        background: linear-gradient(
-29deg,#616d86,#1f1c2c)!important;
}
a, span {
  color:#fff!important;
  font-size: 18px;
}
.navbar-brand {
    color: #fff;
    font-size: 30px;
}
</style>
