<script lang="ts">
  import Header from "$lib/components/Header.svelte";
  import MainContent from "$lib/components/MainContent.svelte";
  import Cards from "$lib/components/Cards.svelte";
  import CompAdvantage from "$lib/components/CompAdvantage.svelte";
</script>

<main>
  <Header />
  <section>
    <Cards />
    <MainContent />
    <CompAdvantage />
  </section>
</main>

<style>
  main {
    display: flex;
    flex-flow: column nowrap;
    justify-content: flex-start;
    align-items: center;

    gap: 3rem;
    padding: 2rem;
    background: #181818;
    height: 100%;
  }

  section {
    display: flex;
    flex-flow: row;
    justify-content: center;
    align-items: center;
    height: 100%;
  }
</style>
