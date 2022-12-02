<script>
import TheNavVue from './components/TheNav.vue';
import Banner from './components/Banner.vue';
import TheFooter from './components/TheFooter.vue';
import SocialBanner from './components/SocialBanner.vue';


export default {
  data() {
    return {

    }
  },
  components: {
    TheNavVue,
    TheFooter,
    Banner,
    SocialBanner
  }
}


</script>

<template>
  <TheNavVue></TheNavVue>
</template>

<style lang="scss">
@use "./styles/general.scss"
</style>
