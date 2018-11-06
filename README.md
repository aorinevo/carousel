# Introduction

Fully responsive Carousel built on Vue.  

# How to Integrate

First install `carousel` in your project: `npm install --save @aorinevo/carousel`.  

Then import the files you need:
```js
<template>
  <carousel :interval="8000" showControls>
    <carousel-item img src="https://mdbootstrap.com/img/Photos/Slides/img%20(68).jpg" alt="First slide" />
    <carousel-item img src="https://mdbootstrap.com/img/Photos/Slides/img%20(6).jpg" alt="Second slide" />
    <carousel-item img src="https://mdbootstrap.com/img/Photos/Slides/img%20(9).jpg" alt="Third slide" />
  </carousel>
</template>

<script>
import { Carousel, CarouselItem } from 'mdbvue';

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
```

For move examples, see `/src/examples`.

# Background

This project componentizes mdb's version of Carousel into a separate npm package. See https://mdbootstrap.com/docs/vue/advanced/carousel/ for more.

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
