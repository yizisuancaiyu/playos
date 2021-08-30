<template>
  <div class="home">
    <Nav />
    <Banner />
    <PerfectTechnology />
    <Partner />
    <Playos />
    <Channels />
    <Footer />
  </div>
</template>

<script>
import Nav from '@/components/nav.vue';
import Banner from './components/banner.vue';
import Footer from '@/components/footer.vue';
import PerfectTechnology from './components/perfect-technology.vue';
import Channels from './components/channels.vue';
import Partner from './components/partner.vue';
import Playos from './components/playos.vue';

export default {
  name: 'home',
  components: {
    Nav,
    Banner,
    Footer,
    PerfectTechnology,
    Channels,
    Partner,
    Playos,
  },
};
</script>

<style lang="scss" scoped>
.home {
  background: url("~@/assets/home-bg.png") repeat-y center top;
}
</style>
