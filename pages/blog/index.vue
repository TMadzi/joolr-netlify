<template>
  <div>
    <div class="blog-top">
      <b-container>
        <b-row>
          <b-col cols="12" lg="5">
            <h1 class="blog-heading">Blog Posts</h1>
          </b-col>
          <b-col cols="12" lg="7" class="mt-2">
            <b-row>
              <b-col
                v-for="blog of blogs"
                :key="blog.slug" cols="12"
                lg="6" class="blog-col" 
                data-aos="fade-up"
              >
                <img :src="blog.img" />
                <h3>{{ blog.title }}</h3>
                <p class="blog-text">{{ blog.description }}</p>
              </b-col>
            </b-row>
          </b-col>
        </b-row>
      </b-container>
    </div>
  </div>
</template>
<template>
<script>
export default {
  async asyncData({ $content, params }) {
    const blogs = await $content('blogs', params.slug)
      .only(['title', 'description', 'img', 'slug', 'author'])
      .sortBy('createdAt', 'asc')
      .fetch()
    return { blogs }
  }
}
</script>
<style scoped>
.blog-top {
  height: auto;
  background-color: #14a1c1;
  padding: 120px 20px 10px 20px;
}

.blog-bottom {
  height: auto;
  background-color: black;
  padding: 60px 20px 10px 20px;
}

.blog-heading {
  line-height: 4.5rem;
  font-size: 4.5rem;
  width: 100%;
  font-weight: bold;
  color: #138099;
}

.blog-bottom-heading {
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

/* .blogs-bottom-heading {
  padding-left: 40px;
} */

.blog-col {
  padding: 0px 20px 20px 20px;
}

.blog-text {
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
  .blog-top {
    height: 100vh;
    background-color: #14a1c1;
    padding-top: 120px;
    padding: 120px 80px 10px 80px;
  }
  .blog-bottom {
    height: auto;
    background-image: url('../assets/images/blog-img.png');
    background-position: center;
    background-size: cover;
    padding: 120px 80px 10px 80px;
  }
  .blog-heading {
    line-height: 5.5rem;
    font-size: 5.5rem;
    width: 100px;
    font-weight: bold;
    color: #138099;
  }

  .blog-bottom-heading {
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
