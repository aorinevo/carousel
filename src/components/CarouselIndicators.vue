<template>
  <component :is="tag" :class="className"><slot></slot></component>
</template>

<script>
import classNames from 'classnames';

const CarouselIndicators = {
  props: {
    tag: {
      type: String,
      default: "ol"
    }
  },
  computed: {
    className() {
      return classNames(
        'carousel-indicators'
      );
    }
  }
};

export default CarouselIndicators;
</script>

<style scoped>
</style>
