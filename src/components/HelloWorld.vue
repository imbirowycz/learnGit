<template>
  <div class="hello">
    <h2>To jest nowa treść</h2>
    <span>To jestem ja</span>
    <p>hello</p>
    <span>Ala ma kota</span>
    <ul>
      <li>dkfjkj</li>
      <li>dkjfdkfj</li>
      <li>dkjfkdfj</li>
    </ul>
    <br>
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
h1, h2 {
  font-weight: normal;
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
