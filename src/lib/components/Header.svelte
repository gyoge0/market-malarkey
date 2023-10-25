<div id="outer">
  <h1>Market Malarkey</h1>

  <div id="group">
    <span>Your Revenue: <strong>320</strong></span>
    <span>|</span>
    <span>Opponent Revenue: <strong>570</strong></span>
  </div>
</div>

<style>
  #outer {
    display: flex;
    flex-flow: row nowrap;
    justify-content: flex-start;
    align-items: center;
    background-color: mediumpurple;

    width: 100%;
    padding-top: 0.25rem;
    padding-bottom: 0.25rem;
    padding-left: 1.5rem;
    padding-right: 1.5rem;
    border-radius: 3rem;
  }

  h1 {
    font-family: "Playfair Display Variable", sans-serif;
    font-weight: bold;
    font-size: 3em;
    flex-grow: 0;
  }

  #group {
    display: flex;
    flex-flow: row nowrap;
    justify-content: flex-end;
    align-items: center;
    flex-grow: 1;
    font-size: 2em;
    gap: 1rem;
    font-family: "Verdana", sans-serif;
  }
  strong {
    font-weight: bold;
    font-size: 1.25em;
  }
</style>
