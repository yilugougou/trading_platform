<template>
  <div class="circle">
    <div class="text">
      {{msg}}
    </div>
    <div class="image">
      <img src="../assets/logo.png" style="width: 50px;height: 50px;" />
      <img src="../assets/logo.png" style="width: 50px;height: 50px;" />
      <img src="../assets/logo.png" style="width: 50px;height: 50px;" />
    </div>
    <div class="more">

    </div>
    <div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'MyCircle',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
