<template>
  <div class="home">
    <Header />
    <Hero />
    <WomenBanner />
    <Insta />
    <Partner />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'
import Header from '@/components/Header.vue'
import Hero from '@/components/Hero.vue'
import WomenBanner from '@/components/WomenBanner.vue'
import Insta from '@/components/Insta.vue'
import Partner from '@/components/Partner.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    Header,
    Hero,
    WomenBanner,
    Insta,
    Partner,
    Footer
  }
}
</script>
