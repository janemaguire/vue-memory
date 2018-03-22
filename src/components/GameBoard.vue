<template>
<div class="game-board">
  <div class="game-cards" v-for="(card, i) of 12">
    <GameCard/>
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
