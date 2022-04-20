<template>
  <div class="error-page">
    <div class="error-background"></div>
    <div
      class="
        error-content
        d-flex
        flex-column
        justify-content-center
        align-items-center
      "
    >
      <h1 class="error-message" v-if="error.statusCode === 404">
        Page not found
      </h1>
      <h1 class="error-message" v-else>An error occurred</h1>
      <div class="">
        <h2 class="go-home-btn position-relative --separate-top p-4">
          <NuxtLink to="/">Go Home</NuxtLink>
        </h2>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: ["error"],
  layout: "error",
};
</script>

<style scoped>
.error-page {
  width: 100vw;
  height: 100vh;
  position: relative;
}
.error-background {
  /* background: url("/img/error-background.png"); */
  filter: grayscale(80%);
  background-size: cover;
  background-position: center;
  width: 100vw;
  height: 100vh;
}
.error-content {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-shadow: 0px 0px 1px #333;
}
.error-message {
  color: var(--main-color);
}
.go-home-btn {
  color: #fff;
}
</style>