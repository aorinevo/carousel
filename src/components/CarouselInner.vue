<template>
  <component :is="tag" :class="className" role="listbox"><slot></slot></component>
</template>

<script>
import classNames from 'classnames';

const CarouselInner = {
  props: {
    tag: {
      type: String,
      default: "div"
    }
  },
  computed: {
    className() {
      return classNames(
        'carousel-inner'
      );
    }
  }
};

export default CarouselInner;
</script>

<style scoped>
</style>
