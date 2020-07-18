<template>
  <!-- Hero Section Begin -->
    <section class="hero-section">
        <carousel class="hero-items" :items="1" :nav="false">
          <div v-for="(item, i) in uriImage" :key="i">
            <div class="single-hero-items set-bg"  :style="{ 'background-image': 'url(' + item.photo + ')' }">
                <div class="container">
                    <div class="row">
                        <div class="col-lg-5">
                            <span>Bag,kids</span>
                            <h1>Black friday</h1>
                            <p>
                                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore
                            </p>
                            <a href="#" class="primary-btn">Shop Now</a>
                        </div>
                    </div>
                </div>
            </div>
          </div>
        </carousel>
    </section>
    <!-- Hero Section End -->
</template>

<script>
import carousel from 'vue-owl-carousel'

export default {
    components: { carousel },
    data(){
      return {
        uriImage: [
          {photo: '/img/hero-1.jpg'},
          {photo: '/img/hero-2.jpg'},
          {photo: '/img/hero-3.jpg'},          
        ]
      }
    }
}
</script>

<style>

</style>