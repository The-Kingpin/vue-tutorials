<template>
  <div class="home">
    <div>
      <img class="robot" src="../assets/robot-home.png" aria-hidden="true" />
    </div>
    <div class="get-started">
      <a href="">Get Started</a> building you first rbot!
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
  props: {
    msg1: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.home {
  text-align: center;
}

.logo {
  height: 300px;
}



</style>
