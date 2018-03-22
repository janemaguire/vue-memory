<template>
<div class="game-card">
  <p>Game Card</p>
</div>
</template>

<script>
export default {
  name: 'GameCard',
  data() {
    return {
      msg: 'I am the card'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .game-card {
    background-color: grey;
    height: 10vh;
    width: 10vh;
    border: 0.2rem solid white;
    border-radius: 1rem;
  }

  p {
    margin: 0;
  }
</style>
