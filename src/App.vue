<template>
  <div id="app">
    <HelloWorld/>
    <GameBoard/>
    <GameCard/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import GameBoard from './components/GameBoard'
import GameCard from './components/GameCard'

export default {
  name: 'App',
  components: {
    HelloWorld,
    GameBoard,
    GameCard
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
