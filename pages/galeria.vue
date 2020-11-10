<template>
  <div>
    <div class="pageTitle">Galeria</div>
    <div class="wrapper">
      <div class="grid">
        <div class="img"><img src="@/assets/img/Rectangle-6.png" alt="" /></div>
        <div class="img"><img src="@/assets/img/Rectangle-6.png" alt="" /></div>
        <div class="img"><img src="@/assets/img/Rectangle-6.png" alt="" /></div>
        <div class="img"><img src="@/assets/img/Rectangle-6.png" alt="" /></div>
        <div class="img"><img src="@/assets/img/Rectangle-6.png" alt="" /></div>
        <div class="img"><img src="@/assets/img/Rectangle-6.png" alt="" /></div>
        <div class="img"><img src="@/assets/img/Rectangle-6.png" alt="" /></div>
        <div class="img"><img src="@/assets/img/Rectangle-6.png" alt="" /></div>
        <div class="img"><img src="@/assets/img/Rectangle-6.png" alt="" /></div>
        <div class="img"><img src="@/assets/img/Rectangle-6.png" alt="" /></div>
        <div class="img"><img src="@/assets/img/Rectangle-6.png" alt="" /></div>
        <div class="img"><img src="@/assets/img/Rectangle-6.png" alt="" /></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang='scss'>
.grid {
  margin-top: 10vh;
  display: grid;
  grid-template: "1fr 1fr 1fr";
  grid-gap: 30px;
  .img {
    width: 300px;
    img {
      width: 100%;
    }
  }
}
</style>
