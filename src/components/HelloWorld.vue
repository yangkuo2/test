<template>
  <div class="body">
    <div class="data">
     <span>黄片</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.body{
  margin: 0;
  padding: 0;
}
.data{
  width: 100%;
  height: 50px;
  background: red;
}
</style>
