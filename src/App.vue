<template>
  <div>
    <Header />
    <About />
    <Portfolio />
    <Partners />
    <Contact />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import About from './components/About.vue'
import Portfolio from './components/Portfolio.vue'
import Partners from './components/Partners.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    About,
    Portfolio,
    Partners,
    Contact,
    Footer
  }
}
</script>
