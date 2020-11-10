<template>
  <div>
    <Header />
    <Nuxt />
    <Footer />
  </div>
</template>
<script>
import Header from "@/components/Header";
import Footer from "@/components/Footer";
export default {
  components: { Header, Footer },
};
</script>

<style lang="scss">
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
  overflow-x: hidden;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
.wrapper {
  width: 1100px;
  margin: 0 auto;
}
.dark-red {
  color: $dark-red;
}
.red {
  color: $red;
}
.block.light-grey {
  background-color: $light-grey;
}
h1 {
  color: $blue;
  font-size: 60px;
}
button {
  width: 255px;
  height: 70px;
  border: none;
  background-color: $dark-red;
  color: white;
  border-radius: 5px;
}
button.small {
  width: 160px;
  height: 70px;
}
.block {
  width: 154px;
  height: 220px;
  background-color: $blue;
  position: relative;
  top: 0;
  left: 0;
}
</style>



