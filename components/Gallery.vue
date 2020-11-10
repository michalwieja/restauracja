<template>
  <div class="gallery">
    <div class="title">Galeria zdjęć</div>
    <p>
      Excepteur sint occaecat cupidatat non proident sunt iculpa qui officia
      deserunt mollit anim est. laborum sed perspiciatis unde omnis natus error
      sit voluptatem accusantium dolor
    </p>
    <div class="images">
      <div class="image">
        <img src="@/assets/img/Rectangle-6.png" alt="" />
      </div>
      <div class="image">
        <img src="@/assets/img/Rectangle-6.png" alt="" />
      </div>
      <div class="image">
        <img src="@/assets/img/Rectangle-6.png" alt="" />
      </div>
      <div class="image">
        <img src="@/assets/img/Rectangle-6.png" alt="" />
      </div>
      <div class="image">
        <img src="@/assets/img/Rectangle-6.png" alt="" />
      </div>
      <div class="image">
        <img src="@/assets/img/Rectangle-6.png" alt="" />
      </div>
    </div>
    <button>Zobacz więcej zdjęć</button>
  </div>
</template>

<script>
export default {};
</script>

<style lang='scss' >
.gallery {
  margin-top: 10vh;
  height: 900px;
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
  align-items: center;
  .title {
    font-size: 40px;
    font-weight: bold;
    text-align: center;
  }
  p {
    font-family: "poppins";
  }
  .images {
    overflow: hidden;
    display: grid;
    grid-template: "1fr 1fr 1fr";
    grid-gap: 30px;

    justify-content: space-between;
    .image {
      width: 350px;
      img {
        width: 100%;
      }
    }
  }
}
</style>