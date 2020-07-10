<template>
  <div class="home">
    <MyCircle msg="Welcome to My Circle."/>
  </div>
</template>

<script>
import MyCircle from '@/components/MyCircle.vue'

export default {
  name: 'Home',
  components: {
    MyCircle
  }
}
</script>
<style>
  body {
    margin: 0px;
  }
</style>