<script>
  import NewsHeader from './components/NewsHeader.svelte';
  import HomepageHero from './components/HomepageHero.svelte';
  import BenefitsBlock from './components/BenefitsBlock.svelte';
  import StatsBlock from './components/StatsBlock.svelte';
  import DataBlock from './components/DataBlock.svelte';
  import FooterBlock from './components/FooterBlock.svelte';

  const blocks = [
    NewsHeader,
    HomepageHero,
    BenefitsBlock,
    StatsBlock,
    DataBlock,
    FooterBlock
  ];
</script>

<main>
  <header class="page-header">
    <p>Figma source node: <code>9210:1629</code></p>
    <h1>Engine Layout (Header, Home, Benefits, Stats, Data, Footer)</h1>
  </header>

  <section class="stack">
    {#each blocks as Block}
      <svelte:component this={Block} />
    {/each}
  </section>
</main>

<style>
  main {
    max-width: 1240px;
    margin: 0 auto;
    padding: 28px 20px 60px;
  }

  .page-header {
    margin-bottom: 20px;
  }

  h1 {
    margin: 8px 0 0;
    font-size: clamp(1.5rem, 3vw, 2.2rem);
    color: #ffffff;
  }

  p {
    margin: 0;
    color: #b6bdd0;
  }

  code {
    font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, 'Liberation Mono', 'Courier New', monospace;
    color: #d7def5;
  }

  .stack {
    display: flex;
    flex-direction: column;
    gap: 14px;
  }
</style>
