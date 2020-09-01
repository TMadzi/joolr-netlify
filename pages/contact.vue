<template>
  <div>
    <div class="contact">
      <b-container>
        <b-row>
          <b-col md="5">
            <h1 class="contact-heading">Contact Us</h1>
          </b-col>
          <b-col md="7" class="contact-top">
            <h1 class="contact-text">
              We always have time for the things you put first.
            </h1>
            <b-form class="contact-form" method="POST" netlify>
              <b-form-group
                id="input-group-2"
                label="First Name:"
                label-for="input-2"
              >
                <b-form-input
                  id="input-2"
                  class="contact-input"
                  required
                  placeholder="FIRST NAME"
                ></b-form-input>
              </b-form-group>
              <b-form-group
                id="input-group-3"
                label="Last Name:"
                label-for="input-3"
              >
                <b-form-input
                  id="input-3"
                  class="contact-input"
                  required
                  placeholder="LAST NAME"
                ></b-form-input>
              </b-form-group>
              <b-form-group
                id="input-group-1"
                label="Email address:"
                label-for="input-1"
              >
                <b-form-input
                  id="input-1"
                  type="email"
                  class="contact-input"
                  required
                  placeholder="EMAIL ADDRESS"
                ></b-form-input>
              </b-form-group>
              <b-form-textarea
                id="textarea-rows"
                class="contact-input"
                placeholder="MESSAGE"
                rows="4"
              ></b-form-textarea>
              <b-button type="submit" class="contact-btn">
                SEND MESSAGE
              </b-button>
            </b-form>
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
<style>
.contact {
  height: auto;
  background-color: #1e252c;
}

.contact-form {
  padding: 0 40px;
}

.contact-top {
  height: auto;
  padding-top: 140px;
}

.contact-text {
  color: #cbd2db;
  text-align: center;
  font-size: 24px;
  position: relative;
  width: 100%;
  padding: 0 15px;
  transition: all 300ms ease;
}

.contact-heading {
  color: #cbd2db;
  text-align: center;
  font-size: 42px;
  position: relative;
  width: 100%;
  top: 101px;
  transition: all 300ms ease;
}

.contact-input {
  background-color: transparent;
  color: white;
  border: none;
  border-radius: 0;
  border-bottom: 2px solid white;
}

.contact-input:focus {
  color: white;
  background-color: transparent;
  border-color: #80bdff;
  outline: 0;
  box-shadow: none;
}
.contact-btn {
  text-transform: uppercase;
  background-color: transparent;
  padding: 15px 40px;
  border-radius: 0;
  border-width: 2px;
  width: 100%;
  border-color: #cbd2db;
  margin: 40px 0;
  transition: all 300ms ease;
}

.contact-btn:hover {
  color: #1e252c;
  background-color: #cbd2db;
  border-color: #cbd2db;
  transition: all 300ms ease;
}
/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 600px) {
}
/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
  .contact-heading {
    transform: rotateZ(-90deg);
    color: #cbd2db;
    font-size: 72px;
    position: relative;
    width: 420px;
    top: 260px;
    transition: all 300ms ease;
  }

  .contact-text {
    color: #cbd2db;
    text-align: left;
    font-size: 36px;
    padding: 0 40px;
    position: relative;
    width: 520px;
    transition: all 300ms ease;
  }
}
/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
  .contact-btn {
    width: 200px;
  }
}
/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
}
</style>
