<template>
  <div>
    <header class="header" :class="scrollHeader">
      <img src="img/onmesmall.jpg" alt="" />
      <label for="check" class="open">
        <i class="fa-solid fa-bars"></i>
      </label>
      <!--nav pc -->
      <nav class="pc">
        <ul>
          <li><a href="">Wellcom</a></li>
          <li><a href="">Home</a></li>
          <li><a href="">Live stream</a></li>
          <li><a href="">Discover</a></li>
          <li><a href="">Gallery</a></li>
        </ul>
      </nav>
      <!--end nav pc-->
    </header>

    <input type="checkbox" id="check" class="opencheck" style="display: none" />
    <label for="check" class="overlay"></label>
    <!-- nav moblie-->
    <nav class="mobie">
      <label for="check" class="close">
        <i class="fa-solid fa-xmark"></i>
      </label>
      <input
        type="checkbox"
        class="opencheck"
        id="check"
        style="display: none"
      />
      <ul>
        <li><a href="">wellcom</a></li>
        <li><a href="">Home</a></li>
        <li><a href="">Live stream</a></li>
        <li><a href="">Discover</a></li>
        <li><a href="">Gallery</a></li>
      </ul>
    </nav>
  </div>
</template>
<script>
export default {
  name: "Header",
  data() {
    return {
      scrollHeader: "",
    };
  },
  mounted() {
    this.addscroll();
  },
  methods: {
    action_scroll() {
      console.log(window.scrollY);
      if (window.scrollY > 100) {
        this.scrollHeader = "headerscroll";
      } else {
        this.scrollHeader = "";
      }
    },
    addscroll() {
      window.addEventListener("scroll", this.action_scroll);
    },
  },
};
</script>

