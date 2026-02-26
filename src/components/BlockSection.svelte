<script>
  export let title;
  export let nodeId;
  export let width = 1440;
  export let height = 700;
  export let summary = '';
  export let eyebrow = 'ENGINE ONLINE';
  export let cta = 'Explore';
  export let stats = [];
  export let tone = 'dark';

  $: minPreviewHeight = Math.max(260, Math.min(height * 0.4, 520));
</script>

<section class={`block ${tone}`} data-node-id={nodeId}>
  <header class="heading">
    <div>
      <p class="eyebrow">{eyebrow}</p>
      <h2>{title}</h2>
      <p class="summary">{summary}</p>
    </div>
    <button type="button">{cta}</button>
  </header>

  <div class="canvas" style={`min-height:${minPreviewHeight}px`}>
    <div class="meta">
      <span>Node {nodeId}</span>
      <span>{width} x {Math.round(height)} px</span>
    </div>
    <div class="stats">
      {#each stats as stat}
        <article>
          <p class="label">{stat.label}</p>
          <p class="value">{stat.value}</p>
        </article>
      {/each}
    </div>
  </div>
</section>

<style>
  .block {
    border: 1px solid rgba(255, 255, 255, 0.16);
    border-radius: 20px;
    padding: 26px;
    display: flex;
    flex-direction: column;
    gap: 18px;
    overflow: hidden;
  }

  .dark {
    background: linear-gradient(148deg, #1b1f2f 0%, #10141d 55%, #0b0e14 100%);
  }

  .light {
    background: linear-gradient(148deg, #f6f7fb 0%, #eceff7 100%);
    border-color: rgba(35, 44, 71, 0.12);
  }

  .light .eyebrow,
  .light .summary,
  .light .meta span,
  .light .label {
    color: #5a647e;
  }

  .light h2,
  .light .value {
    color: #121829;
  }

  .light button {
    background: #121829;
    color: #ffffff;
  }

  .heading {
    display: flex;
    justify-content: space-between;
    gap: 16px;
    align-items: flex-start;
  }

  .eyebrow {
    margin: 0;
    font-size: 0.74rem;
    letter-spacing: 0.11em;
    text-transform: uppercase;
    color: #a4adca;
  }

  h2 {
    margin: 8px 0 0;
    color: #ffffff;
    font-size: clamp(1.05rem, 2vw, 1.58rem);
  }

  .summary {
    margin: 10px 0 0;
    color: #b9c3e5;
    max-width: 66ch;
    line-height: 1.45;
  }

  button {
    border: 0;
    border-radius: 999px;
    padding: 10px 16px;
    font-size: 0.92rem;
    background: #f4f6ff;
    color: #0f1423;
    cursor: pointer;
  }

  .canvas {
    border-radius: 14px;
    border: 1px solid rgba(255, 255, 255, 0.14);
    padding: 16px;
    background: linear-gradient(170deg, rgba(255, 255, 255, 0.08), rgba(255, 255, 255, 0.03));
    display: flex;
    flex-direction: column;
    gap: 16px;
  }

  .meta {
    display: flex;
    justify-content: space-between;
    gap: 12px;
  }

  .meta span {
    color: #cad1ea;
    font-size: 0.82rem;
  }

  .stats {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
  }

  article {
    flex: 1 1 180px;
    border-radius: 10px;
    border: 1px solid rgba(255, 255, 255, 0.14);
    padding: 12px;
    background: rgba(6, 9, 16, 0.35);
  }

  .light article {
    border-color: rgba(18, 24, 41, 0.1);
    background: rgba(255, 255, 255, 0.6);
  }

  .label,
  .value {
    margin: 0;
  }

  .label {
    color: #9da6c4;
    font-size: 0.76rem;
    text-transform: uppercase;
    letter-spacing: 0.07em;
  }

  .value {
    color: #ffffff;
    margin-top: 6px;
    font-size: 1.05rem;
    font-weight: 600;
  }

  @media (max-width: 700px) {
    .heading {
      flex-direction: column;
    }

    button {
      width: 100%;
    }
  }
</style>
