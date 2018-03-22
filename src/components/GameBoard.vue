<template>
<div class="game-board">
  <GameCard/>
</div>
</template>

<script>
import GameCard from '../components/GameCard'

export default {
  name: 'GameBoard',
  components: {
    GameCard
  },
  data() {
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
    height: 50vh;
    width: 50vw;
    border-radius: 1rem;
    padding: 1rem;
  }
</style>
