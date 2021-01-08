<template>
  <nav class="main-nav">
    <img src="../assets/tubaro.jpg" alt="" class="main-nav__list-img">
    <ul class="main-nav__list">
      <li class="main-nav__list-item"><a href="" class="main-nav__list-link">home</a></li>
      <li class="main-nav__list-item"><a href="" class="main-nav__list-link">about</a></li>

      <li class="main-nav__list-item"><a href="" class="main-nav__list-link">gallery</a></li>
      <li class="main-nav__list-item"><a href="" class="main-nav__list-link">contact</a></li>
    </ul>
  </nav>
</template>

<script>
export default {
name: "MainNav"
}
</script>

<style scoped lang="scss">
  .main-nav {
    margin-top: 2.5rem;
  }
  .main-nav__list {
    list-style: none;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: -70px;
  }
  .main-nav__list-img {
    width: 100px;
    border-radius: 50%;
    margin: 0 auto;
    border: 1px solid #eee;
  }

  .main-nav__list-link {
    color: #fff;
    text-transform: uppercase;
    text-decoration: none;
    font-size: 1.3rem;
    letter-spacing: 0.2rem;
  }

  .main-nav__list-item {
    margin: 0 4rem;
  }
  .main-nav__list-item:nth-of-type(3) {
    margin-left: 5rem;

  }

  .main-nav__list-item:nth-of-type(2) {
    margin-right: 5rem;
  }
</style>
