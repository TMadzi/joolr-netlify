<template>
  <div>
    <div class="about-top">
      <b-container>
        <b-row>
          <b-col cols="12" lg="7">
            <h1 class="about-heading" data-aos="fade-up">About Us</h1>
            <b-img
              src="~/assets/images/about-img.png"
              class="about-image"
              data-aos="fade-up"
            ></b-img>
          </b-col>
          <b-col cols="12" lg="5" class="mt-2" data-aos="fade-up">
            <p class="about-top-text">
              Jool'r is uniquely positioned to help you harness the power of
              technology and creativity to redefine how you market your
              business.
            </p>
            <p class="about-bottom-text" data-aos="fade-up">
              In a time of disruptive digital transformation and shifting market
              conditions, we provide you with the support you need to derive
              quantifiable business value from your marketing efforts.
            </p>
          </b-col>
        </b-row>
      </b-container>
    </div>
    <div class="about-middle">
      <b-container>
        <h1 class="vision-heading" data-aos="fade-up">Our Vision</h1>
        <p class="vision-text" data-aos="fade-up">
          To harness the power of creativity and technology to help African
          brands surpass expectations.
        </p>
      </b-container>
    </div>
    <div class="about-bottom">
      <b-container>
        <div class="centered-div" data-aos="fade-up">
          <b-img
            src="~/assets/images/about-img-2.png"
            class="about-image-2"
            data-aos="fade-up"
          ></b-img>
        </div>
        <b-row class="mt-4 pt-4 mb-4 pb-4">
          <b-col cols="12" lg="6" class="about-col" data-aos="fade-up">
            <h4>1. We are not for everyone:</h4>
            <p>
              We understand that we are not the ideal partner for every business
              and that is why we only take on assignments that we truly believe
              we are able to provide real-world benefits to the business.
            </p>
          </b-col>
          <b-col cols="12" lg="6" class="about-col" data-aos="fade-up">
            <h4>2. Clients as partners:</h4>
            <p>
              The best outputs are created when everyone operates as a single
              unit with common goals. Our success is measured as a team, so we
              intentionally sit on the same side of the table as our clients.
            </p>
          </b-col>
          <b-col cols="12" lg="6" class="about-col" data-aos="fade-up">
            <h4>3. Creativity:</h4>
            <p>
              We breed and nurture a culture of experimentation to unlock never
              before seen solutions. We believe in goal-driven creativity,
              pinpointing the intersection between business goals, user goals,
              and the products and services designed to bring them together.
            </p>
          </b-col>
          <b-col cols="12" lg="6" class="about-col" data-aos="fade-up">
            <h4>4. Collaboration:</h4>
            <p>
              Breaking silos means understanding we don’t know everything and
              that all people and clients have value to us. We create
              multi-disciplinary teams who wear a lot of hats and merge with
              your core team. This approach cuts down on overhead and eliminates
              unnecessary communication channels that cost time and money.
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

.about-heading {
  font-size: 72px;
  padding: 0 30px;
  color: #4a4a4a;
  outline: blue;
  margin-bottom: 1px;
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
  font-size: 2.5rem;
  line-height: 3.5rem;
  font-weight: bold;
  width: 100%;
  padding: 0 30px 60px 30px;
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
    font-size: 3.5rem;
    line-height: 3.5rem;
    font-weight: bold;
    width: 730px;
    padding-top: 100px;
  }
}
/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
}
</style>
