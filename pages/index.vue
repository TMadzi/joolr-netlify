<template>
  <div>
    <b-container fluid>
      <b-row>
        <b-col>
          <h1 class="top-header" data-aos="fade-up">
            We are a creative, social impact marketing agency with technology at
            our core.
          </h1>
        </b-col>
      </b-row>
    </b-container>
    <section class="main-image" data-aos="fade-up"></section>
  </div>
</template>
<style scoped>
.container {
  margin: 0 auto;
}

.top-header {
  padding: 20px 10px;
  width: 100%;
  text-align: center;
  line-height: 0.9;
  margin-top: 100px;
  font-size: 3.5rem;
  font-weight: bold;
}

.main-image {
  background-image: url('https://res.cloudinary.com/defmmlrqg/image/upload/v1627928437/joolr/main-img_sudmf7.png');
  height: 65vh;
  width: 100%;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}

/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 600px) {
}

/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
  .top-header {
    padding: 20px 65px;
    width: 100%;

    line-height: 0.9;
    margin: 120px 0 80px 0;
    font-size: 5rem;
    font-weight: bold;
  }
  .main-image {
    background-image: url('~assets/images/main-img.png/');
    height: 65vh;
    margin: 0 auto 100px auto;
    width: 90%;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
  }
}
/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
}
/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
}
</style>
