<i18n>
{
  "uk": {
    "we": "Ми",
    "create": "І ми створюємо",
    "scroll": "Горни вниз"
  },
  "ru": {
    "we": "мы",
    "create": "И мы создаем",
    "scroll": "горны вниз"
  }
}
</i18n>

<template>
  <div id="hero">
    <div class="text-inner">
      <span class="start">
        {{ $t('we') }}
      </span>

      <h1 class="">
        OLDORCS
      </h1>

      <span class="end">
        {{ $t('create') }}
      </span>
    </div>
    <nuxt-link
      v-scroll-to="{
        el: '#services',
        offset: -120,
      }"
      class="scrolldown_container"
      to="#services"
    >
      <div class="scroll text-inner" data-scroll-to="services">
        {{ $t('scroll') }}
      </div>

      <div class="scrolldown text-inner" data-scroll-to="services">
        <div class="line" />
      </div>
    </nuxt-link>
  </div>
</template>

<script>
export default {
  methods: {},
}
</script>

<style lang="scss" scoped>
a,
.scrolldown_container,
.scroll {
  cursor: pointer;
  text-transform: capitalize;
}

#hero {
  width: 100vw;
  min-height: 480px;
  height: calc(100vh - 100px);

  position: relative;

  background-image: url(~assets/img/homeBackground.jpg);
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-position: center;
  background-size: cover;

  text-align: center;
  display: flex;
  flex-direction: row;
  justify-content: center;

  align-items: center;

  margin-top: 100px;
  margin-bottom: 150px;

  &::before {
    content: '';
    display: block;
    margin-top: 100px;
  }

  @media (max-width: 500px) {
    margin-bottom: 75px;
  }
}

#hero h1 {
  font-family: 'Gobold CYR-LAT';
  font-style: normal;
  font-weight: normal;
  font-size: 126px;
  line-height: 85%;

  color: #ffffff;

  margin: 15px 0;

  @media screen and (max-width: 600px) {
    font-size: 63px;
    margin: 10px 0;
  }
}

#hero span.start,
#hero span.end {
  font-style: normal;
  font-weight: 500;
  font-size: 24px;
  line-height: 29px;
  letter-spacing: 0.05em;
  text-transform: uppercase;

  color: #ffffff;
  display: block;

  @media screen and (max-width: 600px) {
    font-size: 12px;
  }
}
#hero span.start {
  text-align: left;
}
#hero span.end {
  text-align: right;
}

.scroll {
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 29px;

  color: #ffffff;

  position: absolute;
  bottom: 130px;
  left: 75%;
  right: 0;
  margin: 0 auto;
  overflow: hidden;

  transform: rotate(90deg);
  -webkit-transform: rotate(90deg);
  -moz-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  -o-transform: rotate(90deg);
  -webkit-transform: translate(90deg);

  @media screen and (max-width: 600px) {
    width: 100px;
    font-size: 14px;
    bottom: 100px;
    left: 75%;
  }
}

.scrolldown {
  width: 5px;
  height: 60px;
  position: absolute;
  bottom: 0px;
  left: 74.5%;
  right: 0;
  margin: 0 auto;
  overflow: hidden;

  @media screen and (max-width: 600px) {
    width: 3px;
    left: 74.5%;
  }
}

.line {
  width: 100%;
  height: 100%;
  display: block;
  background: linear-gradient(
    to bottom,
    rgba(255, 255, 255, 1) 50%,
    rgba(255, 255, 255, 0) 50%
  );
  background-position: 0 -60px;
  background-size: 100% 200%;
  animation: scrolldown 2200ms cubic-bezier(0.76, 0, 0.3, 1) forwards infinite;
  -webkit-animation: scrolldown 2200ms cubic-bezier(0.76, 0, 0.3, 1) forwards
    infinite;
}

@keyframes scrolldown {
  0% {
    background-position: 0 -60px;
  }

  75% {
    background-position: 0 0;
  }

  100% {
    background-position: 0 60px;
  }
}
</style>
