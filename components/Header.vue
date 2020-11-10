<template>
  <header>
    <div class="wrapper">
      <div class="top">
        tel: <span class="dark-red">799 - 999 - 999</span> mail:
        <span class="dark-red">biuro@gabinet.pl</span>
      </div>
      <div class="bottom">
        <div class="logo">Restauracja/pizzeria</div>
        <nav>
          <ul class="nav-links">
            <li><NuxtLink class="nav-link" to="/">Home</NuxtLink></li>
            <li><NuxtLink class="nav-link" to="/about">O nas</NuxtLink></li>
            <li><NuxtLink class="nav-link" to="/">Oferta</NuxtLink></li>
            <li><NuxtLink class="nav-link" to="/">Galeria</NuxtLink></li>
            <li><NuxtLink class="nav-link" to="/">Blog</NuxtLink></li>
            <li><NuxtLink class="nav-link" to="/">Kontakt</NuxtLink></li>
          </ul>
        </nav>
      </div>
    </div>
  </header>
</template>

<script>
export default { name: "Header" };
</script>


<style lang='scss' scoped>
.top {
  text-align: right;
  margin-top: 18px;
}

.bottom {
  margin-top: 18px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  .logo {
    font-size: 40px;
    color: $dark-red;
  }

  .nav-links {
    display: flex;
    justify-content: space-between;
    list-style: none;
  }
  .nav-link {
    text-decoration: none;
    color: #000000;
    margin-left: 54px;
  }
}
</style>