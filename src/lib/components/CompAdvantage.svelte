<script lang="ts">
  import compAdvantageSvg from "$lib/assets/comp-advantage.svg";
</script>

<div id="main">
  <h2>Comparative Advantage Chart</h2>
  <div id="wrapper">
    <img src={compAdvantageSvg} alt="" />
  </div>
</div>

<style>
  #main {
    display: flex;
    flex-flow: column;
    justify-content: center;
    align-items: center;
    background-color: #bb4198;
    border-radius: 2.5rem;
    gap: 2rem;

    padding: 50px;
  }

  img {
    width: 400px;
    height: 400px;
  }

  #wrapper {
    width: fit-content;
    height: fit-content;
  }
  h2 {
    margin: 0;
    font-family: Verdana, sans-serif;
    font-size: 1.5em;
    text-align: center;
  }
</style>
