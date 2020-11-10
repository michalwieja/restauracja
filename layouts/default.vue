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
.title {
  font-size: 30px;
  font-weight: bold;
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
.cards {
  margin-top: 15vh;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  .card {
    height: 200px;
    width: 300px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
    .title {
      font-size: 24px;
      font-weight: bold;
    }
    p {
      font-size: 16px;
    }
  }
}
.pageTitle {
  margin-top: 10vh;
  background: $dark-red;
  width: 695px;
  height: 127px;
  color: white;
  font-size: 50px;
  font-weight: bold;
  display: flex;
  align-items: center;
  justify-content: flex-end;
  padding-right: 50px;
}
.blue {
  margin-top: 10vh;
  color: white;
  .bg {
    background: url("~assets/img/Rectangle.png");
    background-position: center;
    height: 608px;

    position: absolute;
    z-index: -1;
    left: 0;
    right: 0;
    &::after {
      content: "";
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      height: 100%;
      background-color: $blue;
      opacity: 0.86;
    }
  }

  .content {
    display: flex;
    flex-direction: column;
    height: 608px;
    justify-content: space-evenly;
    .title {
      text-align: center;
      font-size: 40px;
      font-family: "poppins";
      font-weight: bold;
    }
    .cards {
      margin-top: 0;
      display: flex;
      align-items: center;
      justify-content: space-between;
      .card {
        width: 300px;
        color: white;
        .title {
          font-size: 50px;
          font-weight: bold;
        }

        p {
          font-size: 22px;
        }
      }
    }
  }
}
</style>



