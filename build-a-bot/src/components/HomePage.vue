<template>
  <div class="home">
    <img src="../assets/robot-home.png" alt="" class="robot" aria-hidden="true">
    <div class="get-started">
      <a href="">Getting started</a> building your first robot!
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.home{
  text-align: center;
}

.robot {
  height: 300px;
}
</style>
