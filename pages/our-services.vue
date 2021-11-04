<template>
  <div>
    <div class="about-top">
      <b-container>
        <b-row>
          <b-col cols="12">
            <h1 class="about-heading" data-aos="fade-up">Our Services</h1>
          </b-col>
        </b-row>
        <b-row>
          <b-col cols="12" lg="6">
            <p class="vision-text pt-8" data-aos="fade-up">Our service offerings are a carefully crafted blend of technology and creativity to deliver measurable solutions that will delight you and your stakeholders.</p>

          </b-col>
          <b-col cols="12" lg="6" class="mt-2 text-center" data-aos="fade-up">
            <b-img
              src="https://res.cloudinary.com/defmmlrqg/image/upload/c_scale,w_600/v1636023284/joolr/service-img_wx7can.jpg"
              class="about-image mt-4 mx-auto"
              data-aos="fade-up"
            ></b-img>
          </b-col>
        </b-row>
      </b-container>
    </div>
    <div class="about-middle">
      <b-container>
        <b-row class="mt-4 pt-4">
          <b-col cols="12" lg="6" class="about-col" data-aos="fade-up">
            <h4>Integrated Campaigns</h4>
                <p class="service-text">
                  We create and execute participatory campaigns to engage supporters, consumers or employees.
                </p>
          </b-col>
          <b-col cols="12" lg="6" class="about-col" data-aos="fade-up">
               <h4>New Power Transformation</h4>
                <p class="service-text">
                  We help organisations bring new power methods and mindsets to their organisations, inside and out.
                </p>
          </b-col>
          <b-col cols="12" lg="6" class="about-col" data-aos="fade-up">
            <h4>Collaborative Innovation</h4>
                <p class="service-text">
                  Identify the goals, issues, audiences, theories of change and supporter journeys that can create drive human-centred innovations.
                </p>
          </b-col>
          <b-col cols="12" lg="6" class="about-col" data-aos="fade-up">
                <h4>Purposeful Brands</h4>
                <p class="service-text">
                  We develop strategy, narratives, and identities that launch movements; reframe and define organisations to transform Brand Purpose.
                </p>
          </b-col>
          <b-col cols="12" lg="6" class="about-col" data-aos="fade-up">
            <h4>Business Design</h4>
            <p class="service-text">
              We work with clients to develop new strategies for growth, designed around their Brand Purpose.
            </p>
          </b-col>
          <b-col cols="12" lg="6" class="about-col" data-aos="fade-up">
                 <h4>Performance Marketing</h4>
                <p class="service-text">
                  We combine brand stewardship with science and execution to deliver conversion-focused marketing solutions.
                </p>
          </b-col>
          <b-col cols="12" lg="6" class="about-col" data-aos="fade-up">
                <h4>Digital Design &amp; Development</h4>
                <p class="service-text">
                  We design and develop digital experiences and platforms that drive empathy, participation, and action.
                </p>
          </b-col>
          <b-col cols="12" lg="6" class="about-col" data-aos="fade-up">
                <h4>Content</h4>
                <p class="service-text">
                  We produce graphics, videos, interactive experiences, installations, and other forms of creative content.
                </p>
          </b-col>
        </b-row>
        </b-container>
    </div>
  </div>
</template>

<script></script>

<style scoped>
.about-top {
  padding-top: 140px;
  height: auto;
  background-color: white;
}

h4 {
  text-transform: uppercase;
}

.about-heading {
  font-size: 48px;
  padding: 10px 30px;
  color: #4a4a4a;
  outline: blue;
  margin-bottom: 1px;
}

.service-text {
  color: rgba(0, 0, 0, 0.61);
  padding: 10px 0;
}

.service-text > li{
  padding: 5px;
}

.about-image {
  padding-top: 0;
  width: 90%;
}

.about-top-text {
  padding: 30px;
  font-size: 18px;
  font-weight: bold;
  color: #4a4a4a;
}

.about-bottom-text {
  padding: 0px 30px;
  font-size: 16px;
  color: #4a4a4a;
}

.about-middle {
  height: auto;
  background-color: #e1e9f3;
  background-position: center;
  background-size: cover;
}

.vision-heading {
  color: #cbd2db;
  font-size: 72px;
  position: relative;
  padding: 30px;
}

.vision-text {
  color: #19a2c0;
  font-size: 1.5rem;
  line-height: 2rem;
  font-weight: bold;
  width: 100%;
  padding: 0 30px 10px 30px;
}

.centered-div {
  margin: 0 auto;
  text-align: center;
}

.about-image-2 {
  padding-top: 40px;
  width: 80%;
}

.about-col {
  padding: 60px 60px 0 60px;
}

h4 {
  text-transform: uppercase;
}

/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 600px) {
}

/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
  .about-heading {
  font-size: 72px;
  padding: 0 30px;
  color: #4a4a4a;
  outline: blue;
  margin-bottom: 1px;
}
}
/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
  .about-top {
    padding-top: 180px;
    height: auto;
    background-color: white;
  }

  .about-top-text {
    padding: 60px 80px 10px 80px;
    font-size: 18px;
    font-weight: bold;
    color: #4a4a4a;
  }

  .about-bottom-text {
    padding: 0px 80px;
    font-size: 16px;
    color: #4a4a4a;
  }
  .about-middle {
    height: auto;
    background-color: #e1e9f3;
    background-position: center;
    background-size: cover;
  }
  .vision-heading {
    left: 75%;
    transform: rotateZ(90deg);
    color: #cbd2db;
    font-size: 72px;
    position: relative;
    width: 420px;
    top: 400px;
  }
  .vision-text {
    color: #19a2c0;
    font-size: 2rem;
    line-height: 2.5rem;
    font-weight: bold;
    width: 100%;
    padding-top: 40px;
  }
}
/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
}
</style>
