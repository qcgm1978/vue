<template>
    <div id="app">
        <img src="./assets/logo.png">
        <hello></hello>
        <bootstrap></bootstrap>
    </div>
</template>

<script>
import Hello from './components/Hello'
import Bootstrap from './components/Bootstrap'
export default {
  name: 'app',
  components: {
    Hello,Bootstrap
  }
}
</script>
<style src="./assets/styles/global.scss" lang="scss"></style>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  background:yellowgreen;
}







</style>
<style lang="scss">
    /* write SASS! */
    html {
        body {
            #app {
                background: yellow;
            }
        }
    }
</style>