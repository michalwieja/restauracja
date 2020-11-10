<template>
  <div>
    <div class="pageTitle">Oferta</div>
    <div class="wrapper">
      <div class="box">
        <div class="content">
          <div class="title">
            Cras eget ligula quis mauris pretium tristique
          </div>
          <p>
            Excepteur sint occaecat cupidatat non proident sunt iculpa qui
            officia deserunt mollit anim est. laborum sed perspiciatis unde
            omnis natus
          </p>
          <button>Zobacz więcej</button>
        </div>
        <div class="img">
          <img src="@/assets/img/Rectangle-6.png" alt="" />
        </div>
      </div>
      <div class="box">
        <div class="img">
          <img src="@/assets/img/Rectangle-6.png" alt="" />
        </div>
        <div class="content">
          <div class="title">
            Cras eget ligula quis mauris pretium tristique
          </div>
          <p>
            Excepteur sint occaecat cupidatat non proident sunt iculpa qui
            officia deserunt mollit anim est. laborum sed perspiciatis unde
            omnis natus
          </p>
          <button>Zobacz więcej</button>
        </div>
      </div>
      <div class="box">
        <div class="content">
          <div class="title">
            Cras eget ligula quis mauris pretium tristique
          </div>
          <p>
            Excepteur sint occaecat cupidatat non proident sunt iculpa qui
            officia deserunt mollit anim est. laborum sed perspiciatis unde
            omnis natus
          </p>
          <button>Zobacz więcej</button>
        </div>
        <div class="img">
          <img src="@/assets/img/Rectangle-6.png" alt="" />
        </div>
      </div>
      <div class="box">
        <div class="img">
          <img src="@/assets/img/Rectangle-6.png" alt="" />
        </div>
        <div class="content">
          <div class="title">
            Cras eget ligula quis mauris pretium tristique
          </div>
          <p>
            Excepteur sint occaecat cupidatat non proident sunt iculpa qui
            officia deserunt mollit anim est. laborum sed perspiciatis unde
            omnis natus
          </p>
          <button>Zobacz więcej</button>
        </div>
      </div>
    </div>
  </div>
</template>


<script>
export default {};
</script>

<style lang='scss' scoped>
.box {
  margin-top: 10vh;
  display: flex;
  align-items: center;
  justify-content: space-between;
  .content {
    height: 250px;
    width: 50%;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    .title {
      font-size: 30px;
      font-weight: bold;
    }
  }
}
</style>
