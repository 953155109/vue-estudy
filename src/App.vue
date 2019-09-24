<template>
  <div id="app">
    <a-button type="primary" @click="handleClick">按钮1</a-button>
    <a-button type="primary" @click="handleClick">按钮1</a-button>
  </div>
</template>

<script>


export default {
  name: 'app',
  methods:{
    handleClick(){
      console.log('111')
  }
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
