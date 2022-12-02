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
  <div class="container">
    <TheNavVue></TheNavVue>
  </div>
  <main class='bg-dark text-white'>
    <div class="container p-5">
      -->Content Here --
    </div>
  </main>
  <Banner></Banner>
  <TheFooter></TheFooter>
  <SocialBanner></SocialBanner>


</template>

<style>

</style>
