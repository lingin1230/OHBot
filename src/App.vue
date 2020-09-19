<template>

  <div id="app">

    <img src="./components/img/logo.png">

    <Main></Main>
    <!-- <Week></Week> -->

<!-- ------------------------------- -->

<!-- ------------------------------- -->

  </div>

</template>

<script>


import Main from './components/main'
import Week from './components/week'

export default {
  name: 'App',
  components: {  //註冊組件
    Main,Week,
  },
}

// -------------------------------


// -------------------------------



</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 200px;
}

@media screen and (max-width:600px){
  #app img {
    width: 300px;
  }
}
</style>
