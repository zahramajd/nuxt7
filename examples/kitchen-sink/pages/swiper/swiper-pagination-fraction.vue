<template>
<f7-page>
  <f7-navbar title="Pagination Fraction" back-link="Back"></f7-navbar>
  <div class="page-content">
    <div data-pagination='{"el": ".swiper-pagination", "type": "fraction"}' class="swiper-container swiper-init demo-swiper">
      <div class="swiper-pagination"></div>
      <div class="swiper-wrapper">
        <div class="swiper-slide">Slide 1</div>
        <div class="swiper-slide">Slide 2</div>
        <div class="swiper-slide">Slide 3</div>
        <div class="swiper-slide">Slide 4</div>
        <div class="swiper-slide">Slide 5</div>
        <div class="swiper-slide">Slide 6</div>
        <div class="swiper-slide">Slide 7</div>
        <div class="swiper-slide">Slide 8</div>
        <div class="swiper-slide">Slide 9</div>
        <div class="swiper-slide">Slide 10</div>
      </div>
    </div>
  </div>
</f7-page>
</template>
<script>
  import { f7Navbar, f7Page } from 'framework7-vue';

  export default {}
</script>
