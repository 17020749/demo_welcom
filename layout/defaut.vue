<template>
  <div>
    <Header />
    <div>
      <Nuxt />
    </div>
    <Footer />
  </div>
</template>

<script>
import Header from "../components/Header";
import Footer from "../components/Footer";
export default {
  name: "Defaut",
  components: [Header,Footer],

};
</script>




