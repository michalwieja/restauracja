<template>
  <div>
    <Header />
    <Nuxt />
  </div>
</template>
<script>
import Header from "@/components/Header";
export default {
  components: { Header },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@400;700&family=Poppins:wght@400;700&display=swap");
html {
  font-family: "Josefin Sans", sans-serif;
  font-size: 18px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}
.wrapper {
  width: 1100px;
  margin: 0 auto;
}
.dark-red {
  color: $dark-red;
}
</style>



