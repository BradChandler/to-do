<template>
  <section>
    <Header />
    <router-view></router-view>
    <Footer />
  </section>
</template>

<script>
import Header from "./components/Includes/Header/index.vue";
import Footer from "./components/Includes/Footer/index.vue";
export default {
  components: {
    Header, 
    Footer
  }
}
</script>