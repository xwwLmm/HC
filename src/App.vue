<template>
  <div>
    <div id="app">
      <tab></tab>
      <router-view></router-view>
    </div>
  </div>

</template>

<script>
  import Tab from 'views/tab/index'
  export default {
    name: 'app',
    components: {
      Tab
    }
  }
</script>

<style lang="less">
  #app {
    text-align: center;
    color: #2c3e50;
    margin: 20px auto;
    box-shadow: 0 0 12px #5e5e5e;
    max-width: 1180px;

  }

  body {
    background: #fff url('assets/body.jpg');
    background-size: cover;
  }
</style>
