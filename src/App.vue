<template>
  <div id="app">
    <Header />
    <Spotlight />
    <Features />
    <Youtube />
    <Playlist />
    <Mailing />
    <Plans />
    <Articles />
    <CTA />
    <Sponsor />
    <Main />
    <Footer />

  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Spotlight from "./components/Spotlight.vue";
import Playlist from "./components/Playlist.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";
import Features from "./components/Features.vue";
import Youtube from "./components/Youtube.vue";
import Mailing from "./components/Mailing.vue";
import Plans from "./components/Plans.vue";
import Articles from "./components/Articles.vue";
import CTA from "./components/CTA.vue";
import Sponsor from "./components/Sponsor.vue";










export default {
  name: "App",
  components: {
    Header,
    Main,
    Playlist,
    Footer,
    Spotlight,
    Features,
    Youtube,
    Mailing,
    Plans,
    Articles,
    CTA,
    Sponsor,
  },
};
</script>

<style lang="scss">
@import "/home/giacomo/Documents/Boolean/avada/src/assets/sass/style.scss";


</style>
