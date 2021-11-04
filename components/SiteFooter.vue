<template>
  <footer>
    <b-container>
      <b-row>
        <b-col cols="12" md="4">
          <b-link to="/">
            <b-img
              src="~/assets/images/log-new.svg/"
              alt="Joolr Logo"
              class="logo-footer"
            >
            </b-img>
          </b-link>
        </b-col>
        <b-col cols="4" md="2">
          <b-nav class="nav-bottom" vertical>
            <b-nav-item to="/">Home</b-nav-item>
            <b-nav-item to="/about-us">About</b-nav-item>
          </b-nav>
        </b-col>
        <b-col cols="4" md="2">
          <b-nav class="nav-bottom" vertical>
            <b-nav-item to="/solutions">Solutions</b-nav-item>
            <b-nav-item to="/collaboration-models">Collaboration</b-nav-item>
          </b-nav>
        </b-col>
        <b-col cols="4" md="2">
          <b-nav class="nav-bottom" vertical>
            <b-nav-item to="/our-services">Services</b-nav-item>
            <b-nav-item to="/contact">Contact</b-nav-item>
          </b-nav>
        </b-col>
        <b-col cols="4" md="2">
          <b-nav class="nav-bottom" vertical>
            <b-nav-item
              href="https://www.linkedin.com/company/jool-r"
              target="blank"
            >
              LinkedIn
            </b-nav-item>
            <b-nav-item
              href="https://www.twitter.com/joolr_africa"
              target="blank"
            >
              Twitter
            </b-nav-item>
          </b-nav>
        </b-col>
      </b-row>
    </b-container>
  </footer>
</template>
<style>
footer {
  height: 100%;
  background-color: #e1e9f3;
  padding: 20px;
}

.nav-bottom {
  margin-top: 40px !important;
}

.logo-footer {
  height: auto;
  margin-top: 40px;
  width: 180px;
}

ul {
  line-height: 1;
}

.nav-link {
  color: black;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
</style>
