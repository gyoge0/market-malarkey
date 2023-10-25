<script lang="ts">
  import playingCardBack from "$lib/assets/playing_card_back.png";
</script>

<div id="main">
  <div id="draw">
    <img src={playingCardBack} alt="" />
  </div>
  <div id="play">
    <h2>No cards yet!</h2>
  </div>
</div>

<style>
  #main {
    display: flex;
    flex-flow: column;
    width: 50rem;
    background-color: #c460a7;
    height: 100%;
    border-radius: 2.5rem;
    align-items: center;
    padding-top: 3rem;
    gap: 2rem;
  }

  #play {
    display: flex;
    flex-flow: row wrap;
  }

  #draw {
    border-style: solid;
    border-width: 0.5rem;
    border-radius: 1.5rem;
    border-color: #482a3d;
  }

  #draw > img {
    width: 100%;
    height: 100%;
  }

  h2 {
    margin: 0;
    font-family: Verdana, sans-serif;
  }
</style>
