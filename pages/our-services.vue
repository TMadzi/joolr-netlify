<template>
  <div>
    <div class="service-top">
      <b-container>
        <b-row>
          <b-col cols="12" lg="5">
            <h1 class="service-heading">Our Services</h1>
          </b-col>
          <b-col cols="12" lg="7" class="mt-2">
            <b-row>
              <b-col cols="12" lg="6" class="service-col" data-aos="fade-up">
                <h3>Marketing and analytics</h3>
                <p class="service-text">
                  Your marketing dollars support diverse activities and
                  audiences that demand a more sophisticated approach to
                  maximising spend. Through the use of modern analytics
                  technologies, to bring a data-driven approach to your
                  marketing efforts that will excite the CFO and delight your
                  customers.
                </p>
              </b-col>
              <b-col cols="12" lg="6" class="service-col" data-aos="fade-up">
                <h3>Technology</h3>
                <p class="service-text">
                  No matter the solution, a tech stack must be adaptable and
                  grow with the pace of change. With a network of
                  multi-disciplinary developers and engineers, we combine agile
                  product development with the latest frameworks to reduce your
                  technical debt and build scalable solutions that work for your
                  users and your business.
                </p>
              </b-col>
              <b-col cols="12" lg="6" class="service-col" data-aos="fade-up">
                <h3>Brand Management</h3>
                <p class="service-text">
                  With a focus on client engagement and
                  eturn-on-Marketing-Investment, we are able to quantify the
                  financial value of your brand and find every opportunity to
                  convey its most authentic and memorable voice to your market.
                </p>
              </b-col>
              <b-col cols="12" lg="6" class="service-col" data-aos="fade-up">
                <h3>Creative Design</h3>
                <p class="service-text">
                  We harness the power of creativity to craft stunning,
                  intuitive and engaging expressions of your brand. Through our
                  creative approach to problem solving, we start with the
                  consideration of the people we are designing for and end with
                  new solutions that are tailor-made to suit their needs.
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
          <b-col>
            <h1 class="service-bottom-heading" data-aos="fade-up">
              Our Services
            </h1>
          </b-col>
        </b-row>
        <b-row>
          <b-col lg="4" class="service-col" data-aos="fade-up">
            <h3 class="services-bottom-heading">Marketing and analytics</h3>
            <ul class="service-text">
              <li>A/B Testing</li>
              <li>Anova Analysis</li>
              <li>Conjoint Analysis</li>
              <li>Sentiment Analysis</li>
              <li>Data Visualisation</li>
            </ul>
          </b-col>
          <b-col
            lg="4"
            offset-lg="4"
            class="service-col service-right"
            data-aos="fade-up"
          >
            <h3 class="services-bottom-heading">Technology</h3>
            <ul class="service-text">
              <li>Web Design &amp; Development</li>
              <li>Enterprise Software Development</li>
              <li>Mobile App Development</li>
              <li>Custom Software</li>
              <li>Sofware as a Service</li>
            </ul>
          </b-col>
          <b-col lg="4" class="service-col" data-aos="fade-up">
            <h3 class="services-bottom-heading">Brand Management</h3>
            <ul class="service-text">
              <li>Strategy</li>
              <li>Valuation</li>
              <li>Content Development</li>
              <li>Digital &amp; Social Media</li>
              <li>Audio, Visual &amp; Digial Production</li>
            </ul>
          </b-col>
          <b-col
            lg="4"
            offset-lg="4"
            class="service-col service-right"
            data-aos="fade-up"
          >
            <h3 class="services-bottom-heading">Creative Design</h3>
            <ul class="service-text">
              <li>Graphic Design</li>
              <li>Prototyping</li>
              <li>Content Development</li>
              <li>Human Centered Design</li>
              <li>Corporate Identity</li>
              <li>Asset Branding</li>
            </ul>
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
    height: 100vh;
    background-color: #14a1c1;
    padding-top: 120px;
    padding: 120px 80px 10px 80px;
  }
  .service-bottom {
    height: auto;
    background-image: url('~assets/images/service-img.png');
    background-position: center;
    background-size: cover;
    padding: 120px 80px 10px 80px;
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
