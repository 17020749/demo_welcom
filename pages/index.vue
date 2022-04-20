<template>
  <div class="welcom">
    <Header />
    <div class="main"></div>
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
export default {
  name: "IndexPage",
  // layout: "defaut",
};
</script>
