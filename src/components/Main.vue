<template>
  <div id="main">
    <img class="main__image" src="../assets/tubaro.jpg" />
  </div>
</template>

<script>
export default {
  name: 'Main',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .main__image {
    width: 600px;
    box-shadow: -5px 5px 50px -15px #2a2a2a;
  }

  @media only screen and (max-width: 800px) {
    .main__image {
      width: 500px;
    }
  }
</style>
