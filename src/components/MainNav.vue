<template>
  <nav class="main-nav">
    <img src="../assets/tubaro-small.jpg" alt="" class="main-nav__list-img">
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
    margin: 2rem 0 7rem 0;
  }
  .main-nav__list {
    list-style: none;
    display: flex;
    justify-content: center;
    margin-top: -70px;
    margin-left: 2rem;
  }
  .main-nav__list-img {
    width: 100px;
    border-radius: 50%;
    margin: 0 auto;
    border: 1px solid #666;
    filter: blur(0px) grayscale(100%);
    -webkit-filter: blur(0px) grayscale(100%);
    transition:all 0.3s ease;

    &:hover {
      border-color: transparent;
      filter: blur(1px) grayscale(100%);
      -webkit-filter: blur(1px) grayscale(100%);
    }
  }

  .main-nav__list-link {
    color: #fff;
    text-transform: uppercase;
    text-decoration: none;
    font-size: 1.3rem;
    letter-spacing: 0.3rem;
    transition: all 0.3s ease;

    &:hover {
      cursor: pointer;
      color: #210710;
      text-shadow: 0px 0px 20px #210710;
    }
  }

  .main-nav__list-item {
    margin: 0 5.5rem;
    text-align: center;
  }

  .main-nav__list-item:nth-of-type(1) {
    margin-right: 0;

  }

  .main-nav__list-item:nth-of-type(4) {
    margin-left: 0;
  }
</style>
