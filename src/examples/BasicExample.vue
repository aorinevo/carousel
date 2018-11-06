<template>
  <carousel :interval="8000" showControls>
    <carousel-item img src="https://mdbootstrap.com/img/Photos/Slides/img%20(68).jpg" alt="First slide" />
    <carousel-item img src="https://mdbootstrap.com/img/Photos/Slides/img%20(6).jpg" alt="Second slide" />
    <carousel-item img src="https://mdbootstrap.com/img/Photos/Slides/img%20(9).jpg" alt="Third slide" />
  </carousel>
</template>

<script>
import { Carousel, CarouselItem } from '../../';

export default {
  name: 'CarouselPage',
  components: {
    Carousel,
    CarouselItem
  }
};
</script>

<style scoped>
</style>
