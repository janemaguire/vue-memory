<template>
<div class="home-page">
  <h1>{{ msg }}</h1>
  <GameBoard/>
</div>
</template>

<script>
import GameBoard from '../components/GameBoard'
export default {
  name: 'HomePage',
  components: {
    GameBoard
  },
  data() {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.home-page {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>
