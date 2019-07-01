<template>
  <section class="hero">
    <div class="hero__background">
      <video autoplay muted loop id="myVideo" >
        <source src="/img/hero.mov">
      </video>
    </div>
    <div class="hero__wrap">
        <div class="hero__top fw">
          <div class="hero__logo">
            <img  src="/img/logo.svg" alt="">
          </div>
          <div class="hero__nav">
            <ul class="fw">
              <li>{{ $t('advantages')}}</li>
              <li>{{ $t('functions')}}</li>
              <li>{{ $t('Contact us')}}</li>
            </ul>
          </div>
          <!-- <select class="hero__language" v-model="$i18n.locale">
            <option v-for="(lang, i) in langs" :key="`Lang${i}`" :value="lang">{{ lang }}</option>
          </select> -->
        </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'hero',
  data () {
    return { langs: ['ja', 'en'] }
  }
}
</script>






