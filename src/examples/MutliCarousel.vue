<template>
  <container class="mt-5">
    <carousel :interval="8000" showControls showIndicators multi slide>
      <carousel-item>
        <row>
          <column md="4">
            <card class="mb-2">
              <card-img src="https://mdbootstrap.com/img/Photos/Horizontal/Nature/4-col/img%20(34).jpg" alt="Card image cap" waves></card-img>
              <card-body>
                <card-title>Card title</card-title>
                <card-text>Some quick example text to build on the card title and make up the bulk of the card's content.</card-text>
                <btn color="primary">Button</btn>
              </card-body>
            </card>
          </column>
          <column md="4" class="clearfix d-none d-md-block">
            <card class="mb-2">
              <card-img src="https://mdbootstrap.com/img/Photos/Horizontal/Nature/4-col/img%20(18).jpg" alt="Card image cap" waves></card-img>
              <card-body>
                <card-title>Card title</card-title>
                <card-text>Some quick example text to build on the card title and make up the bulk of the card's content.</card-text>
                <btn color="primary">Button</btn>
              </card-body>
            </card>
          </column>
          <column md="4" class="clearfix d-none d-md-block">
            <card class="mb-2">
              <card-img src="https://mdbootstrap.com/img/Photos/Horizontal/Nature/4-col/img%20(35).jpg" alt="Card image cap" waves></card-img>
              <card-body>
                <card-title>Card title</card-title>
                <card-text>Some quick example text to build on the card title and make up the bulk of the card's content.</card-text>
                <btn color="primary">Button</btn>
              </card-body>
            </card>
          </column>
        </row>
      </carousel-item>
      <carousel-item>
        <row>
          <column md="4">
            <card class="mb-2">
              <card-img src="https://mdbootstrap.com/img/Photos/Horizontal/Nature/4-col/img%20(60).jpg" alt="Card image cap" waves></card-img>
              <card-body>
                <card-title>Card title</card-title>
                <card-text>Some quick example text to build on the card title and make up the bulk of the card's content.</card-text>
                <btn color="primary">Button</btn>
              </card-body>
            </card>
          </column>
          <column md="4" class="clearfix d-none d-md-block">
            <card class="mb-2">
              <card-img src="https://mdbootstrap.com/img/Photos/Horizontal/Nature/4-col/img%20(47).jpg" alt="Card image cap" waves></card-img>
              <card-body>
                <card-title>Card title</card-title>
                <card-text>Some quick example text to build on the card title and make up the bulk of the card's content.</card-text>
                <btn color="primary">Button</btn>
              </card-body>
            </card>
          </column>
          <column md="4" class="clearfix d-none d-md-block">
            <card class="mb-2">
              <card-img src="https://mdbootstrap.com/img/Photos/Horizontal/Nature/4-col/img%20(48).jpg" alt="Card image cap" waves></card-img>
              <card-body>
                <card-title>Card title</card-title>
                <card-text>Some quick example text to build on the card title and make up the bulk of the card's content.</card-text>
                <btn color="primary">Button</btn>
              </card-body>
            </card>
          </column>
        </row>
      </carousel-item>
      <carousel-item>
        <row>
          <column md="4">
            <card class="mb-2">
              <card-img src="https://mdbootstrap.com/img/Photos/Horizontal/Nature/4-col/img%20(53).jpg" alt="Card image cap" waves></card-img>
              <card-body>
                <card-title>Card title</card-title>
                <card-text>Some quick example text to build on the card title and make up the bulk of the card's content.</card-text>
                <btn color="primary">Button</btn>
              </card-body>
            </card>
          </column>
          <column md="4" class="clearfix d-none d-md-block">
            <card class="mb-2">
              <card-img src="https://mdbootstrap.com/img/Photos/Horizontal/Nature/4-col/img%20(45).jpg" alt="Card image cap" waves></card-img>
              <card-body>
                <card-title>Card title</card-title>
                <card-text>Some quick example text to build on the card title and make up the bulk of the card's content.</card-text>
                <btn color="primary">Button</btn>
              </card-body>
            </card>
          </column>
          <column md="4" class="clearfix d-none d-md-block">
            <card class="mb-2">
              <card-img src="https://mdbootstrap.com/img/Photos/Horizontal/Nature/4-col/img%20(51).jpg" alt="Card image cap" waves></card-img>
              <card-body>
                <card-title>Card title</card-title>
                <card-text>Some quick example text to build on the card title and make up the bulk of the card's content.</card-text>
                <btn color="primary">Button</btn>
              </card-body>
            </card>
          </column>
        </row>
      </carousel-item>
    </carousel>
  </container>
</template>

<script>
import { Carousel, CarouselItem, CarouselCaption } from '../components';

export default {
  name: 'CarouselPage',
  components: {
    Carousel,
    CarouselItem,
    CarouselCaption,
    Container,
    Row,
    Column,
    Card,
    CardImg,
    CardBody,
    CardTitle,
    CardText,
    Btn
  }
};
</script>

<style scoped>
</style>
