<template>
  <div class="header">
      <h1>{{msg}}</h1>
  </div>
</template>

<script>
  export default {
    name: 'header',
    data () {
      return {
        msg: '这个是头部'
      }
    }
  }
</script>
