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
.block {
  width: 154px;
  height: 220px;
  background-color: $blue;
  position: relative;
  top: 0;
  left: 0;
}
</style>



