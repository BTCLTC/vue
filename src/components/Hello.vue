<template>
  <div class="hello">
    <h1 class="text">{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data() {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
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
.hello {
  .text {
    text-align: center;
    background-image: -webkit-linear-gradient(left, #0acbe9, #ff0000 25%, #ff2ee1 50%, #fffc00 75%, #11eb97);
    -webkit-text-fill-color: transparent;
    -webkit-background-clip: text;
    -webkit-background-size: 200% 100%;
    -webkit-animation: masked-animation 4s infinite linear;
  }

  @-webkit-keyframes masked-animation {
      0%{ background-position: 0 0;}
      100% { background-position: -100% 0;}
  }
}

</style>
