<script lang="ts">
  import Header from "$lib/components/Header.svelte";
</script>

<main>
  <Header />
</main>

<style>
  main {
    width: 100%;
    height: 100%;
    display: flex;
    flex-flow: column nowrap;
    justify-content: flex-start;
    align-items: center;

    padding: 2rem;
    background: #181818;
  }
</style>
