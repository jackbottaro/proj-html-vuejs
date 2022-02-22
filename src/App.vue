<template>
  <div id="app">
    <Header :navigations="navs"/>
    <Spotlight />
    <Features />
    <Youtube />
    <Playlist />
    <Mailing />
    <Plans />
    <Articles />
    <CTA />
    <Sponsor />
    <Events />
    <Main />
    <Footer />
    <FixexButtons />

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
import Events from "./components/Events.vue";
import FixexButtons from "./components/FixexButtons.vue";












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
    Events,
    FixexButtons,
  },
  data() {
    return {
      navs: [
        { link: "#", text: "Home" },
        { link: "#", text: "Service" },
        { link: "#", text: "About" },
        { link: "#", text: "Videos" },
        { link: "#", text: "Blog" },
        { link: "#", text: "Store" },
      ],
    }
  }
};
</script>

<style lang="scss">
@import "/home/giacomo/Documents/Boolean/avada/src/assets/sass/style.scss";

</style>
