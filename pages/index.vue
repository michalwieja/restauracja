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
    <div class="meet">
      <div class="img">
        <img src="@/assets/img/Rectangle-1.png" alt="" />
        <div class="block"></div>
      </div>
      <div class="content">
        <div class="title">Meet cool new people over the world</div>
        <p>
          Excepteur sint occaecat cupidatat non proident sunt iculpa qui officia
          deserunt mollit anim est. laborum sed perspiciatis unde omnis natus
          error sit voluptatem accusantium dolore mque laudantium totam rem
          aperiam. Dicta sunt explicabo. nemo enim ipsam voluptatem quia magni
          voluptassit aspernatur aut odit aut fugit sed quia consequuntur magni
          dolores eos.
        </p>
        <button>join us</button>
      </div>
    </div>
    <div class="blue">
      <div class="bg">
        <!-- <img src="@/assets/img/Rectangle.png" alt="" /> -->
      </div>
      <div class="content">
        <div class="title">
          Excepteur sint occaecat cupidatat non proident sunt iculpa qui officia
          deserunt
        </div>
        <div class="cards">
          <div class="card">
            <div class="title">900+</div>
            <p>Wykonanych zabiegów</p>
          </div>
          <div class="card">
            <div class="title">12 515</div>
            <p>Zadowolonych pacjentów</p>
          </div>
          <div class="card">
            <div class="title">15</div>
            <p>Lat doświadczenia</p>
          </div>
        </div>
      </div>
    </div>
    <div class="meet">
      <div class="content">
        <div class="title">Meet cool new people over the world</div>
        <p>
          Excepteur sint occaecat cupidatat non proident sunt iculpa qui officia
          deserunt mollit anim est. laborum sed perspiciatis unde omnis natus
          error sit voluptatem accusantium dolore mque laudantium totam rem
          aperiam. Dicta sunt explicabo. nemo enim ipsam voluptatem quia magni
          voluptassit aspernatur aut odit aut fugit sed quia consequuntur magni
          dolores eos.
        </p>
        <button>join us</button>
      </div>
      <div class="img">
        <img src="@/assets/img/Rectangle-2.png" alt="" />
        <div class="block light-grey"></div>
      </div>
    </div>
    <div class="news">
      <div class="bg"></div>
      <div class="title">Aktualności</div>

      <div class="cards">
        <div class="card">
          <img src="@/assets/img/Rectangle-3.png" alt="" />
          <small class="dark-red">QUIS AUTEM VEL EUM</small>
          <div class="title">
            Cras eget ligula quis mauris pretium tristique
          </div>
          <p>
            Excepteur sint occaecat cupidatat non proident sunt iculpa qui
            officia deserunt mollit anim est.
          </p>
          <button class="small">Read More</button>
        </div>
        <div class="card">
          <img src="@/assets/img/Rectangle-4.png" alt="" />
          <small class="dark-red">QUIS AUTEM VEL EUM</small>
          <div class="title">
            Cras eget ligula quis mauris pretium tristique
          </div>
          <p>
            Excepteur sint occaecat cupidatat non proident sunt iculpa qui
            officia deserunt mollit anim est.
          </p>
          <button class="small">Read More</button>
        </div>
      </div>
    </div>
    <Gallery />
  </div>
</template>

<script>
import Gallery from "@/components/Gallery";
export default {};
</script>

<style lang='scss' scoped>
.bestPizza {
  margin-top: 10vh;
  width: 100%;
  display: flex;
  align-items: center;
  position: relative;

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

  .img {
    position: relative;
    width: 895px;
    height: 646px;
    .block {
      top: -110px;
      left: 100px;
    }
  }
}

.meet {
  margin-top: 15vh;
  display: flex;
  justify-content: space-between;
  .img {
    .block {
      width: 100%;
      height: 100%;
      top: -550px;
      left: 50px;
      z-index: -1;
    }
  }
  .content {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    width: 500px;
    height: 390px;
    .title {
      font-size: 40px;
      font-weight: bold;
    }
  }
}

.news {
  margin-top: 10vh;
  height: 840px;
  display: flex;
  flex-direction: column;

  .bg {
    position: absolute;
    height: 840px;
    left: 0;
    right: 0;
    background-color: $light-grey;
    z-index: -1;
  }
  .title {
    text-align: center;
    margin-top: 5vh;
    font-size: 40px;
  }
  .cards {
    margin-top: 5vh;

    .card {
      width: 500px;
      height: 570px;
      align-items: start;
      small {
        font-size: 12px;
      }
      .title {
        font-size: 30px;
        text-align: left;
      }
    }
  }
}
</style>
