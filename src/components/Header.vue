<template>
  <div id="header">
    <h1 class="name">aquila aveion</h1>
  </div>
</template>

<script>
export default {
  name: 'Header',
  props: {
    name: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .name {
    margin: 3rem 0;
    padding:0;
    font-weight: 100;
    text-transform: uppercase;
    font-size: 3rem;
    letter-spacing: 0.5rem;
    word-spacing: 1rem;
    color: #fff;
  }
</style>
