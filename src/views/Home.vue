<template>
  <div class="home">
    <header-store></header-store>
    <owl-carousel></owl-carousel>
    <slider-showcase></slider-showcase>
  </div>
</template>

<script>
import HeaderStore from '../components/HeaderStore';
import OwlCarousel from '../components/OwlCarousel'
import SliderShowcase from '../components/SliderShowcase'
export default {
  name: 'Home',
  components: {
    HeaderStore,
    OwlCarousel,
    SliderShowcase
  }
  
}
</script>
