<template>
<div class="game-board">
  <h1>{{ msg }}</h1>
  <h2>Game Board</h2>
</div>
</template>

<script>
export default {
  name: 'GameBoard',
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
  }
</style>
