<template>
  <div class="social-links">
    <ul class="social-links__list">
      <li class="social-links__list-item"><a href="" class="social-links__list-link"><i class="fa fa-instagram" aria-hidden="true"></i></a></li>
      <li class="social-links__list-item"><a href="" class="social-links__list-link"><i class="fa fa-twitter-square" aria-hidden="true"></i></a></li>
      <li class="social-links__list-item"><a href="" class="social-links__list-link"><i class="fa fa-snapchat-square" aria-hidden="true"></i></a></li>
      <li class="social-links__list-item"><a href="" class="social-links__list-link"><i class="fa fa-envelope" aria-hidden="true"></i></a></li>
    </ul>
  </div>
</template>

<script>
export default {
name: "SocialLinks"
}
</script>

<style scoped lang="scss">
  .social-links__list {
    position: absolute;
    top: 50%;
    right: 1rem;
    transform: translateY(-50%);
    list-style: none;
    font-size: 2.5rem;

    .social-links__list-item {
      margin-bottom: 1.5rem;
    }

    .social-links__list-link {
      color: #fff;
    }
  }
</style>
