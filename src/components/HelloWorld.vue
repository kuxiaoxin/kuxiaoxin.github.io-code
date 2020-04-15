<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h1>你好呀，鱼非道。</h1>
    <h2>你好呀，鱼非道。</h2>
    <h3>你好呀，鱼非道。</h3>
    <h4>你好呀，鱼非道。</h4>
    <h5>你好呀，鱼非道。</h5>
    <p>你好呀，鱼非道。</p>
    <p>
      For a guide and recipes on how to configure / customize this project,<br>
      check out the.
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

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
