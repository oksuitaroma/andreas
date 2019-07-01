<template>
  <section class="gallery">
    <div class="gallery__wrap">
      <div class="gallery__line"></div>
      <div class="gallery__title">
        <h3>Video gallery</h3>
      </div>
      <div class="gallery__cards">
        
          <carousel
          :items='5'
          :loop='true'
          :autoplay='true'
          :center='true'
          :dots="false"
          >
            <div class="gallery__card-wr">
              <div class="gallery__card">
                <img src="/img/card1.png" alt="card">
                <img  class="gallery__play" src="/img/play.png" alt="play">
              </div>
            </div>
            <div class="gallery__card-wr">
              <div class="gallery__card">
                <img src="/img/card1.png" alt="card">
                <img  class="gallery__play" src="/img/play.png" alt="play">
              </div>
            </div>
            <div class="gallery__card-wr">
              <div class="gallery__card">
                <img src="/img/card1.png" alt="card">
                <img  class="gallery__play" src="/img/play.png" alt="play">
              </div>
            </div>
            <div class="gallery__card-wr">
              <div class="gallery__card">
                <img src="/img/card1.png" alt="card">
                <img  class="gallery__play" src="/img/play.png" alt="play">
              </div>
            </div>
            <div class="gallery__card-wr">
              <div class="gallery__card">
                <img src="/img/card1.png" alt="card">
                <img  class="gallery__play" src="/img/play.png" alt="play">
              </div>
            </div>
            <div class="gallery__card-wr">
              <div class="gallery__card">
                <img src="/img/card1.png" alt="card">
                <img  class="gallery__play" src="/img/play.png" alt="play">
              </div>
            </div>
            <div class="gallery__card-wr">
              <div class="gallery__card">
                <img src="/img/card1.png" alt="card">
                <img  class="gallery__play" src="/img/play.png" alt="play">
              </div>
            </div>
            <!-- <template slot="prev"><span class="prev"><img  src="/img/arrow.png" alt="arrow"></span></template>
            <template slot="next"><span class="next"><img  src="/img/arrow.png" alt="arrow"></span></template> -->
        </carousel>
        
        
      </div>
      <div class="gallery__line"></div>
    </div>
  </section>
</template>

<script>
  import carousel from 'vue-owl-carousel'

  export default {
    components: { carousel },
  }
</script>