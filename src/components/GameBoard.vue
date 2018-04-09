<template>
<div class="game-board">
  <div class="game-card" v-for="item of 20" :key="item.id">
      <GameCard />
  </div>
</div>
</template>

<script>
import GameCard from '../components/GameCard'

export default {
  name: 'GameBoard',
  components: {
    GameCard
  },
  data () {
    return {
      msg: 'I am the board'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.game-board {
  background-color: pink;
  height: 60vh;
  width: 50vw;
  border-radius: 1vw;
  padding: 1vw;
  display: grid;
  grid-template-columns: auto auto auto auto;
}
.game-card {
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
