<template>
  <div class="welcom">
    <Header />
    <div class="main"></div>
    <Footer />
  </div>

</template>
<style scoped>
.main {
  width: auto;
  height: 1200px;
}
.welcom {
  background-image: url("../static/img/onme.png");
  background-size: 100%;
  background-repeat: no-repeat;
}
</style>
<script>
import Footer from "../components/Footer.vue"
export default {
  name: "IndexPage",
  components: [Footer],
  //layout: "defaut",
};
</script>
