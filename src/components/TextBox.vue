<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <textarea v-model="message" placeholder=""></textarea>
        <br>
    <p style="white-space: pre-line;">{{ message }}</p>
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
