<template>
  <div id="app">    
    <router-view  ></router-view>
  </div>
</template>

<script>
export default {
  name: 'notebook'
}
</script>

<style lang="stylus">
@import './assets/lib/normalize'

@font-face
  font-family 'Ubuntu-Bold'
  src url('./assets/fonts/Ubuntu-Bold.woff2') format('woff2')
  font-weight bold
  font-style normal  

body
  font-family Ubuntu-Bold
  font-size 30px
</style>
