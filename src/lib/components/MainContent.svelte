<script lang="ts">
  import supplyDemand1 from "$lib/assets/supply_demand_1.png";
  import supplyDemand2 from "$lib/assets/supply_demand_2.png";
  import supplyDemand3 from "$lib/assets/supply_demand_3.png";
  import supplyDemand4 from "$lib/assets/supply_demand_4.png";
</script>

<div id="main">
  <div class="sd-container">
    <h2>Your Greebe Market</h2>
    <img src={supplyDemand1} alt="supply and demand" />
  </div>
  <div class="sd-container">
    <h2>Your Butter Market</h2>
    <img src={supplyDemand2} alt="supply and demand" />
  </div>
  <div class="sd-container">
    <h2>Opponent's Greebe Market</h2>
    <img src={supplyDemand3} alt="supply and demand" />
  </div>
  <div class="sd-container">
    <h2>Opponent's Butter Market</h2>
    <img src={supplyDemand4} alt="supply and demand" />
  </div>
</div>

<style>
  #main {
    display: flex;
    flex-flow: row wrap;
    gap: 1rem;
    width: fit-content;
    justify-content: center;
  }

  h2 {
    margin: 0;
  }

  #main > div {
    width: 20rem;
    height: 20rem;
  }

  .sd-container {
    display: flex;
    flex-flow: column;
    background-color: #fcbdfc;
    align-items: center;
    border-radius: 2.5rem;
    width: fit-content;
    height: fit-content;
    padding: 1.5rem;
    gap: 1rem;
    font-family: Verdana, sans-serif;
  }

  img {
    border-radius: 1rem;
    height: 200px;
    width: 250px;
    display: block;
    margin: auto;
  }
</style>
