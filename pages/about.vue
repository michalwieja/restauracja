<template>
  <div>
    <div class="pageTitle">O nas</div>
    <div class="wrapper">
      <div class="que">
        <div class="content">
          <h1>Quis Autem Vel Eum Iure</h1>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent
            tempus, est id placerat feugiat, risus arcu porta tortor, nec
            convallis purus magna vitae justo. Suspendisse et venenatis ligula.
          </p>
        </div>
        <div class="img">
          <img src="@/assets/img/Rectangle-5.png" alt="" />
        </div>
      </div>
      <div class="cards">
        <div class="card">
          <div class="icon">
            <img src="@/assets/img/burger.png" alt="" />
          </div>
          <div class="title">Fast food</div>
          <p>
            Etiam maximus, justo ut pellentesque egestas, erat sapien mollis
            massa, nec porta nisl quam eu arcu. Donec sit amet congue lectus
          </p>
        </div>
        <div class="card">
          <div class="icon">
            <img src="@/assets/img/heart.png" alt="" />
          </div>
          <div class="title">Pysznie</div>
          <p>
            Etiam maximus, justo ut pellentesque egestas, erat sapien mollis
            massa, nec porta nisl quam eu arcu. Donec sit amet congue lectus
          </p>
        </div>
        <div class="card">
          <div class="icon">
            <img src="@/assets/img/fruit.png" alt="" />
          </div>
          <div class="title">Także zdrowo</div>
          <p>
            Etiam maximus, justo ut pellentesque egestas, erat sapien mollis
            massa, nec porta nisl quam eu arcu. Donec sit amet congue lectus
          </p>
        </div>
        <div class="card">
          <div class="icon">
            <img src="@/assets/img/cocktail.png" alt="" />
          </div>
          <div class="title">Drink Bar</div>
          <p>
            Etiam maximus, justo ut pellentesque egestas, erat sapien mollis
            massa, nec porta nisl quam eu arcu. Donec sit amet congue lectus
          </p>
        </div>
      </div>
      <div class="blue">
        <div class="bg">
          <!-- <img src="@/assets/img/Rectangle.png" alt="" /> -->
        </div>
        <div class="content">
          <div class="title">
            Excepteur sint occaecat cupidatat non proident sunt iculpa qui
            officia deserunt
          </div>
          <button class="transparent">Join Us</button>
          <div class="block"></div>
        </div>
      </div>
      <Gallery />
    </div>
  </div>
</template>

<script>
import Gallery from "@/components/Gallery";

export default {};
</script>

<style scoped lang='scss'>
.que {
  margin-top: 10vh;
  display: flex;
  align-items: center;
  .content {
    margin-right: 200px;
  }
  .img {
    position: relative;
    &::before {
      content: "";
      position: absolute;
      top: -100px;
      left: 100px;
      width: 100%;
      height: 100%;
      background-color: $light-grey;
      z-index: -1;
    }
  }
}
.card {
  width: 250px;
}
.blue {
  .bg {
    height: 405px;
  }
  .content {
    height: 405px;
    align-items: center;
  }
  button {
    border: 1px solid white;
    background: none;
  }
  .block {
    position: relative;
    height: 139px;
    width: 97px;
    top: 70px;
    left: -50%;
    background-color: $dark-red;
  }
}
</style>
