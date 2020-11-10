<template>
  <div class="wrapper">
    <div class="bestPizza">
      <div class="content">
        <h1>Najlepsza pizza w mieście</h1>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent
          tempus, est id placerat feugiat, risus arcu porta tortor, nec
          convallis purus magna vitae justo. Suspendisse et venenatis ligula.
        </p>
        <button>Zobacz ofertę</button>
      </div>
      <div class="img">
        <img src="@/assets/img/its-a-pizza-gathering-BQK8EBD.png" alt="" />
        <div class="block"></div>
      </div>
    </div>
    <div class="cards">
      <div class="card">
        <div class="icon"><img src="@/assets/img/fast-food.png" alt="" /></div>
        <div class="title">Ochrona zdrowia</div>
        <p>
          Etiam maximus, justo ut pellentesque egestas, erat sapien mollis
          massa, nec porta nisl quam eu arcu. Donec sit amet congue lectus
        </p>
      </div>
      <div class="card">
        <div class="icon"><img src="@/assets/img/fast-food.png" alt="" /></div>
        <div class="title">Satysfakcja pacjenta</div>
        <p>
          Etiam maximus, justo ut pellentesque egestas, erat sapien mollis
          massa, nec porta nisl quam eu arcu. Donec sit amet congue lectus
        </p>
      </div>
      <div class="card">
        <div class="icon"><img src="@/assets/img/fast-food.png" alt="" /></div>
        <div class="title">Profesjonalny zespół</div>
        <p>
          Etiam maximus, justo ut pellentesque egestas, erat sapien mollis
          massa, nec porta nisl quam eu arcu. Donec sit amet congue lectus
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang='scss' scoped>
.img {
  position: relative;
  width: 895px;
  height: 646px;
}
.bestPizza {
  margin-top: 10vh;
  width: 100%;
  display: flex;
  align-items: center;
  position: relative;
}
.content {
  position: relative;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  flex: 0 0 auto;
  margin-right: 100px;
  height: 425px;
  width: 550px;
}
.block {
  top: -110px;
  left: 100px;
}

.cards {
  margin-top: 15vh;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}
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
</style>
