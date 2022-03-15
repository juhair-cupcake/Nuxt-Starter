<template>
  <div>
    <Navigation />
    <Nuxt />
    <Footer />
  </div>
</template>
<script>
import Footer from "/components/Footer";
import Navigation from "/components/Navigation";
export default {
  components: {
    Footer,
    Navigation,
  },
};
</script>
