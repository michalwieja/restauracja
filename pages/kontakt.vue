<template>
  <div>
    <div class="pageTitle">Kontakt</div>
    <div class="wrapper">
      <div class="info">
        <div class="content">
          <h1>Dane kontaktowe</h1>
          <div class="address">
            Adres: Warszawa 152 ul. Bohaterów Katynia 15 02-533
          </div>
          <div class="contact">
            <div class="tel">
              tel: <br />
              <span class="dark-red">799-900-900</span>
            </div>
            <div class="mail">
              mail: <br />
              <span class="dark-red">biuro@gabinet.pl</span>
            </div>
          </div>
          <div class="socials">IG FB W PR</div>
        </div>
        <div class="map">
          <img src="@/assets/img/mask.png" alt="" />
          <div class="block"></div>
        </div>
      </div>
    </div>
    <div class="bg">
      <div class="wrapper">
        <div class="title">Talk to Us About New Work</div>
        <p>
          Excepteur sint occaecat cupidatat non proident sunt iculpa qui officia
          deserunt mollit anim est. laborum sed perspiciatis unde omnis natus
          error sit voluptatem
        </p>
        <form>
          <input type="text" />
          <input type="text" />
          <input type="text" />
          <input type="text" />
          <button>Read More</button>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang='scss' scoped>
.wrapper {
  margin-top: 10vh;
  .info {
    display: flex;
    .content {
      margin-right: 100px;
      height: 320px;
      position: relative;
      display: flex;
      flex: 0 0 auto;
      flex-direction: column;
      justify-content: space-evenly;
      .address {
        width: 50%;
      }
      .contact {
        display: flex;
        justify-content: space-between;
      }
    }
    .map {
      position: relative;
      .block {
        position: relative;
        width: 82px;
        height: 117px;
        background-color: $dark-red;
        top: -50px;
        left: 80px;
      }
    }
  }
}
.bg {
  height: 810px;
  background: lighten($color: $blue, $amount: 60%);
  .wrapper {
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
    text-align: center;
    .title {
      width: 25%;
    }
    p {
      width: 40%;
    }
    form {
      width: 800px;
      display: grid;
      grid-gap: 30px;
      grid-template: "1fr 1fr";
      input {
        width: 400px;
        height: 70px;
        border-radius: 10px;
        border: none;
      }
      button {
        width: 100%;
        grid-column: 1 / 3;
      }
    }
  }
}
</style>
