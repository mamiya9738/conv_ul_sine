<template>
  <div class="TextBox" >
    <h1>{{ msg }}</h1>
    <textarea v-model="message" placeholder=""></textarea>
        <br>
    <p style="white-space: pre-line;">{{ message }}</p>

  </div>

<div id="app">
    <input type="text" v-model="textInput">
    <p>{{ textInput }}</p>
</div>
</template>

<script>
export default {
    name: 'TextBox',
    props: {
      msg: String , 
  //    message: String , 
    }  
  }

var app = new Vue({
    el: '#app',
    data: {
      textInput: '初期値はここに入れておく',		
    }
  })	


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
