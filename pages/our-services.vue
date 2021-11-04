<template>
  <div>
    <div class="service-top">
      <b-container>
        <b-row>
          <b-col cols="12" lg="4">
            <h1 class="service-heading">Our Services</h1>
          </b-col>
          <b-col cols="12" lg="8" class="mt-2">
            <b-row>
              <b-col cols="12" lg="6" class="service-col" data-aos="fade-up">
                <h3>Integrated Campaigns</h3>
                <p class="service-text">
                  We create and execute participatory campaigns to engage supporters, consumers or employees.
                </p>
              </b-col>
              <b-col cols="12" lg="6" class="service-col" data-aos="fade-up">
                <h3>New Power Transformation</h3>
                <p class="service-text">
                  We help organisations bring new power methods and mindsets to their organisations, inside and out.
                </p>
              </b-col>
              <b-col cols="12" lg="6" class="service-col" data-aos="fade-up">
                <h3>Collaborative Innovation</h3>
                <p class="service-text">
                  Identify the goals, issues, audiences, theories of change and supporter journeys that can create drive human-centred innovations.
                </p>
              </b-col>
              <b-col cols="12" lg="6" class="service-col" data-aos="fade-up">
                <h3>Purposeful Brands</h3>
                <p class="service-text">
                  We develop strategy, narratives, and identities that launch movements; reframe and define organisations to transform Brand Purpose.
                </p>
              </b-col>
            </b-row>
          </b-col>
        </b-row>
      </b-container>
    </div>
    <div class="service-bottom">
      <b-container>
        <b-row>
          <b-col lg="4" class="service-col" data-aos="fade-up">
            <h3>Business Design</h3>
            <p class="service-text">
              We work with clients to develop new strategies for growth, designed around their Brand Purpose.
            </p>
          </b-col>
          <b-col
            lg="4"
            offset-lg="4"
            class="service-col service-right"
            data-aos="fade-up"
          >
                <h3>Performance Marketing</h3>
                <p class="service-text">
                  We combine brand stewardship with science and execution to deliver conversion-focused marketing solutions.
                </p>
          </b-col>
          <b-col lg="4" class="service-col" data-aos="fade-up">
                <h3>Digital Design &amp; Development</h3>
                <p class="service-text">
                  We design and develop digital experiences and platforms that drive empathy, participation, and action.
                </p>
          </b-col>
          <b-col
            lg="4"
            offset-lg="4"
            class="service-col service-right"
            data-aos="fade-up"
          >
                <h3>Content</h3>
                <p class="service-text">
                  We produce graphics, videos, interactive experiences, installations, and other forms of creative content.
                </p>
          </b-col>
        </b-row>
      </b-container>
    </div>
  </div>
</template>
<script>
export default {
  layout: 'lightnav'
}
</script>
<style scoped>
.service-top {
  height: auto;
  background-color: #14a1c1;
  padding: 120px 20px 10px 20px;
}

.service-bottom {
  height: auto;
  background-color: black;
  padding: 60px 20px 10px 20px;
}

.service-heading {
  line-height: 4.5rem;
  font-size: 4.5rem;
  width: 100%;
  font-weight: bold;
  color: #138099;
}

.service-bottom-heading {
  font-size: 64px;
  width: 100px;
  color: #cbd2dbbd;
  padding-top: 40px;
}

h3 {
  color: white;
  text-transform: uppercase;
  font-size: 20px;
}

/* .services-bottom-heading {
  padding-left: 40px;
} */

.service-col {
  padding: 0px 20px 20px 20px;
}

.service-text {
  color: rgba(255, 255, 255, 0.61);
  padding-left: 0;
}

ul {
  list-style: none;
}

/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 600px) {
}

/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
}
/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
  .service-top {
    height: auto;
    background-color: #14a1c1;
    padding-top: 120px;
    padding: 120px 80px 80px 80px;
  }
  .service-bottom {
    height: auto;
    background-image: url('~assets/images/service-img.png');
    background-position: bottom;
    background-size: cover;
    padding: 100px 80px 80px 80px;
  }
  .service-heading {
    line-height: 5.5rem;
    font-size: 5.5rem;
    width: 100px;
    font-weight: bold;
    color: #138099;
  }

  .service-bottom-heading {
    font-size: 72px;
    width: 100px;
    color: #cbd2dbbd;
    padding-top: 40px;
  }
}
/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
}
</style>
