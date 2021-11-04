<template>
  <div>
    <div class="about-top">
      <b-container>
        <b-row>
          <b-col cols="12">
            <h1 class="about-heading" data-aos="fade-up">Collaboration Models</h1>
          </b-col>
        </b-row>
        <b-row>
          <b-col cols="12" lg="6">
            <p class="vision-text" data-aos="fade-up">We understand that budgets and businesses are unique and that is why we have developed models for collaboration that work for you depending on your unique needs.</p>

          </b-col>
          <b-col cols="12" lg="6" class="mt-2 text-center" data-aos="fade-up">
            <b-img
              src="https://res.cloudinary.com/defmmlrqg/image/upload/c_scale,w_700/v1635884726/joolr/colab_nuabvw.jpg"
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
            <h4>Design Consultancy</h4>
            <ul class="service-text">
              <li>Project to project basis</li>
              <li>Fixed deliverables and timelines</li>
              <li>High Clarity brief</li>
            </ul>
          </b-col>
          <b-col cols="12" lg="6" class="about-col" data-aos="fade-up">
            <h4>Service Agreement</h4>
            <ul class="service-text">
              <li>Long term agreement, task based</li>
              <li>Billed on Time and Materials</li>
              <li>Flexible model, accommodates varied design needs</li>
            </ul>
          </b-col>
          <b-col cols="12" lg="6" class="about-col" data-aos="fade-up">
            <h4>Design Partner</h4>
            <ul class="service-text">
              <li>End-to-end ownership of design</li>
              <li>Active co-creation with team</li>
              <li>Integrated design solutions</li>
            </ul>
          </b-col>
          <b-col cols="12" lg="6" class="about-col" data-aos="fade-up">
            <h4>Joint Venture</h4>
            <ul class="service-text">
              <li>Co-create a solution together</li>
              <li>Government and business partnerships</li>
              <li>Product strategy and marketing</li>
              <li>Co-ownership, strategic input</li>
            </ul>
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

.about-heading {
  font-size: 48px;
  padding: 10px 30px;
  color: #4a4a4a;
  outline: blue;
  margin-bottom: 1px;
}

.service-text {
  color: rgba(0, 0, 0, 0.61);
  padding: 10px;
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
    height: 100vh;
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
    height: 100vh;
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
