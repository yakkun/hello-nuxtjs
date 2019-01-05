<template>
  <div>
    <Header/>
    <Hero/>
    <main class="columns">
      <Sidemenu/>
      <nuxt/>
    </main>
    <Footer/>
  </div>
</template>

<script>
import Header from '~/components/Header.vue'
import Hero from '~/components/Hero.vue'
import Sidemenu from '~/components/Sidemenu.vue'
import Footer from '~/components/Footer.vue'
export default {
  components: {
    Header,
    Hero,
    Sidemenu,
    Footer,
  }
}
</script>
