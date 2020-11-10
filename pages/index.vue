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
</style>
