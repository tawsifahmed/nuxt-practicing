<template>
  <div>
    <Header />
    <div class="outlet">
      <Nuxt />
    </div>
    <Footer />
  </div>
</template>

<script>
import Header from "@/components/Header";
import Footer from "@/components/Footer";
export default {
  components: {
    Header,
    Footer,
  },
};
</script>

<style>
.outlet {
  min-height: 100vh;
}
</style>