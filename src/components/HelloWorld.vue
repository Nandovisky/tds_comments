<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Zelda:</h2>
    <ul>
      <li>
        <a href="https://youtube.com/watch?v=dQw4w9WgXcQ" target="_blank">
          awesome-vue
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: ""
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
  color: #0000FF;
}
</style>
