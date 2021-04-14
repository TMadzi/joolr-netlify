<template>
  <div>
    <div class="solution-top">
      <b-container>
        <b-row>
          <b-col cols="12" lg="5">
            <b-row class="custom-head">
              <div>
                <h1 class="solution-heading">Custom Solutions</h1>
                <p class="custom-head-text pr-5">
                  At Jool’r we have developed proprietary custom solutions to
                  meet the varying needs of the African continent. Some of our
                  existing solutions are as follows:
                </p>
              </div>
            </b-row>
          </b-col>
          <b-col cols="12" lg="7" class="mt-2">
            <b-row>
              <b-col cols="12" class="solution-col" data-aos="fade-up">
                <b-img
                  src="~/assets/images/yusure.png"
                  class="solution-image"
                  data-aos="fade-up"
                ></b-img>
                <p class="solutions-text mt-2">
                  Yu’sure is a social enterprise that seeks to tackle the
                  crippling condition of youth unemployment by providing young
                  people with the means to earn income through selling short and
                  long-term insurance products to the people they know. We call
                  these people their “Tribe” as we understand that it is easier
                  to purchase from a well-known source that you have an intimate
                  connection with. As a mobile-first solution, we partner with
                  established insurance providers, to extend their potential
                  client reach without the need for them to establish
                  brick-and-mortar presences in some of the most remote and
                  inaccessible areas in an African country.
                </p>
              </b-col>
              <b-col cols="12" class="solution-col" data-aos="fade-up">
                <b-img
                  src="~/assets/images/koni.png"
                  class="solution-image"
                  data-aos="fade-up"
                ></b-img>
                <p class="solutions-text mt-2">
                  Koni is a capacity building e-learning platform borne out of
                  the need to decentralise learning for corporates, government,
                  and NGOs in Africa. The idea was simple, how do we still allow
                  capacity building to occur remotely in the New Normal? Koni
                  allows our clients to develop customised lessons for their
                  respective organisations, using their own branding and award
                  certificates to individuals who complete these programmes.
                  This widens its application to areas of prerequisite trainings
                  for employment and loans, empowerment programmes and refresher
                  courses in the realms of law, human resources, accounting,
                  finance, policy and strategy. The options for Koni are limited
                  only by the imagination of our clients as we continue to bring
                  a data-driven future into our present..
                </p>
              </b-col>
              <b-col cols="12" class="solution-col" data-aos="fade-up">
                <b-img
                  src="~/assets/images/mario.png"
                  class="solution-image"
                  data-aos="fade-up"
                ></b-img>
                <p class="solutions-text mt-2">
                  Mar.io is a marketing automation and team collaboration
                  platform currently in development. It is very similar to
                  Slack. The idea was borne out of frustration with businesses
                  in Africa using WhatsApp as a communications tool; so Mar.io
                  has all the functions of Slack, but adds to the privacy needs
                  of businesses by centralising all communications onto a client
                  in-house server which the business will set up internally with
                  a back-up on Jool’r’s cloud service.
                </p>
              </b-col>
            </b-row>
          </b-col>
        </b-row>
      </b-container>
    </div>
  </div>
</template>
<style scoped>
.solution-top {
  height: auto;
  background-color: white;
  padding: 120px 20px 10px 20px;
}

.solution-heading {
  line-height: 4.5rem;
  font-size: 4.5rem;
  width: 100%;
  font-weight: bold;
  color: #4a4a4a;
}

h3 {
  color: white;
  text-transform: uppercase;
  font-size: 20px;
}

.solution-col {
  padding: 0px 20px 20px 20px;
}

.solution-image {
  width: 70%;
  margin: 0 auto;
}

.solutions-text {
  font-weight: 400;
  line-height: 2;
  color: #212529;
  text-align: left !important;
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
  .custom-head {
    position: sticky;
    top: 100px;
  }

  .custom-head-text {
    width: 100%;
  }
  .solution-top {
    background-color: white;
    padding-top: 120px;
    padding: 120px 80px 10px 80px;
  }
  .solution-heading {
    line-height: 5.5rem;
    font-size: 5.5rem;
    width: 100px;
    font-weight: bold;
    color: #4a4a4a;
  }
}
/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
}
</style>
