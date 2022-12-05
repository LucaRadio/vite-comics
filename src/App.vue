<script>
import TheNavVue from './components/TheNav.vue';
import Banner from './components/Banner.vue';
import TheFooter from './components/TheFooter.vue';
import SocialBanner from './components/SocialBanner.vue';
import SingleCard from './components/SingleCard.vue';
import CardList from './components/CardList.vue';
import Jumbotrone from './components/Jumbotrone.vue';


export default {
  data() {
    return {

    }
  },
  components: {
    TheNavVue,
    TheFooter,
    Banner,
    SocialBanner,
    SingleCard,
    CardList,
    Jumbotrone
  }
}


</script>

<template>
  <div class="container">
    <TheNavVue></TheNavVue>
  </div>
  <Jumbotrone />
  <main class='bg-dark text-white'>
    <div class="container pt-5">
      <CardList />
    </div>
  </main>
  <Banner></Banner>
  <TheFooter></TheFooter>


</template>

<style lang="scss">

</style>
