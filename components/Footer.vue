<template>
  <footer>
    <div class="wrapper">
      <div class="top">
        <div class="about card">
          <div class="title">Restauracja</div>
          <p>
            Excepteur sint occaecat cupidatat non proident sunt iculpa qui
            officia deserunt mollit anim est. laborum sed perspiciatis unde
            omnis natus error sit voluptatem accusantium dolore mque laudantium
            totam rem aperiam.
          </p>
        </div>
        <div class="offer card">
          <div class="title">Oferta</div>
          <ul>
            <li>Oferta 1</li>
            <li>Numer oferty 2</li>
            <li>Trzeci Numer</li>
            <li>Czwarta oferta</li>
            <li>Piąta oferta</li>
          </ul>
        </div>
        <div class="menu card">
          <div class="title">Menu</div>
          <nav>
            <ul class="nav-links">
              <li><NuxtLink class="nav-link" to="/">Home</NuxtLink></li>
              <li><NuxtLink class="nav-link" to="/">O nas</NuxtLink></li>
              <li><NuxtLink class="nav-link" to="/">Oferta</NuxtLink></li>
              <li><NuxtLink class="nav-link" to="/">Galeria</NuxtLink></li>
              <li><NuxtLink class="nav-link" to="/">Blog</NuxtLink></li>
              <li><NuxtLink class="nav-link" to="/">Kontakt</NuxtLink></li>
            </ul>
          </nav>
        </div>
        <div class="contact card">
          <div class="title">Kontakt z nami</div>
          <div class="tel">
            <p>tel: <span class="red">790 - 900 - 900</span></p>
            <p>mail: <span class="red"> biuro@gainet.pl</span></p>
          </div>
          <div class="socials">IG FB TW PR</div>
          <div class="address">
            Adres: <br />
            Warszawa 152 ul. Bohaterów Katynia 15 02-533
          </div>
        </div>
      </div>
      <div class="bottom">
        <div>Gabinet.pl - gabinet doktora dolore mque laudantium totam</div>
        <div>projekt i wykonanie: projektowaniestron.pl</div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped lang='scss'>
footer {
  position: absolute;
  background-color: #260000;
  height: 500px;
  width: 100%;
  color: white;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  .top {
    display: flex;
    .card {
      height: 200px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .about {
      flex: 2;
      margin-right: 100px;
      .title {
        font-size: 40px;
        font-weight: bold;
      }
      p {
        font-size: 16px;
      }
    }
    .title {
      font-weight: bold;
    }
    ul {
      list-style: none;
      li {
        padding: 2px;
        a {
          color: white;
          text-decoration: none;
        }
      }
    }

    .offer {
      flex: 1;
    }
    .menu {
      flex: 1;
    }
    .contact {
      flex: 1;
    }
  }
  .bottom {
    margin-top: 15vh;
    font-size: 16px;
    display: flex;
    justify-content: space-between;
  }
}
</style>