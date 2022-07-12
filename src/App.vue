<template>
  <TextBox msg="ウルトラサイン変換ツール"/>
</template>

<script>
import TextBox from './components/TextBox.vue'

export default {
  name: 'App',
  components: {
    TextBox
  }
}

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
