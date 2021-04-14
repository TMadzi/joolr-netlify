<template>
  <div>
    <b-container fluid>
      <b-link to="/">
        <b-img src="~/assets/images/logo-4.svg/" alt="Joolr Logo" class="logo">
        </b-img>
      </b-link>
      <div class="navi-toggle">
        <b-button v-b-toggle.sidebar-right class="menu-btn">
          MENU <span class="menu"><img src="~/assets/images/menu.png"/></span>
        </b-button>
        <b-sidebar id="sidebar-right" title="" right backdrop shadow>
          <div class="px-3 py-2">
            <b-nav vertical class="w-25">
              <b-nav-item class="navi-item" to="/">Home</b-nav-item>
              <b-nav-item class="navi-item" to="/our-services"
                >Services</b-nav-item
              >
              <b-nav-item class="navi-item" to="/our-services"
                >Solutions</b-nav-item
              >
              <!-- <b-nav-item class="navi-item" to="/blog">Blog</b-nav-item> -->
              <b-nav-item class="navi-item" to="/about-us">About</b-nav-item>
              <b-nav-item class="navi-item" to="/contact">Contact</b-nav-item>
            </b-nav>
          </div>
        </b-sidebar>
      </div>
    </b-container>
    <nuxt />
    <SiteFooter />
  </div>
</template>
<script>
import SiteFooter from '~/components/SiteFooter.vue'

export default {
  components: {
    SiteFooter
  }
}
</script>
<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

.menu {
  margin-left: 5px;
}

.logo {
  position: absolute;
  height: auto;
  width: 120px;
  left: 40px;
  top: 20px;
  z-index: 1;
}

.nav {
  margin-left: 12%;
  text-align: right;
  font-weight: bold;
  margin-top: 40%;
  margin-bottom: 20px;
  color: #35495e;
}

.navi-toggle {
  position: absolute;
  right: 30px;
  top: 20px;
  z-index: 1;
}

.b-sidebar-header {
  position: absolute;
  right: 5px;
}

.btn-secondary:focus {
  color: black;
  background-color: white;
  border-color: #545b62;
  transition: all 0.5s ease;
  box-shadow: 0 0 0 0.2rem rgba(130, 138, 145, 0);
}

.navi-item {
  font-size: 2.5rem;
  line-height: 1.25;
  margin-bottom: 1.5rem;
  display: inline-block;
  position: relative;
  z-index: 1000;
}

.navi-item::after {
  content: '';
  position: absolute;
  left: 0;
  display: inline-block;
  height: 15px;
  width: 0;
  margin-top: -48px;
  z-index: -1;
  background-color: #14a1c1;
  transition: width 0.3s ease;
}

.navi-item:hover:after {
  content: '';
  position: absolute;
  width: 100%;
  background-color: #14a1c1;
  transition: width 0.4s ease;
}

a:hover {
  color: #35495e;
  transition: all 0.2s ease;
}

.menu-btn {
  color: white;
  background-color: transparent;
  border: none;
  transition: all 0.5s ease;
}

.menu-btn:hover {
  color: #fff;
  background-color: #14a1c1;
  border-color: #545b62;
  transition: all 0.5s ease;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}

.nav-link {
  color: #343a40;
  transition: all 0.5s ease;
}

/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 600px) {
}

/* Landscape */
@media only screen and (orientation: landscape) {
  .nav {
    margin-left: 12%;
    text-align: right;
    font-weight: bold;
    margin-top: 5%;
    margin-bottom: 20px;
    color: #35495e;
  }
  .navi-item {
    font-size: 1.5rem;
    line-height: 1;
  }
}

/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
  .navi-toggle {
    position: fixed;
    right: 80px;
    top: 20px;
    z-index: 1;
  }

  .navi-item {
    font-size: 3.5rem;
    line-height: 1.25;
    margin-bottom: 1.5rem;
    display: inline-block;
    position: relative;
    z-index: 1000;
  }
}

/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
  .logo {
    position: absolute;
    height: auto;
    width: 120px;
    left: 130px;
    top: 20px;
    z-index: 1;
  }
}

/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
}
</style>
