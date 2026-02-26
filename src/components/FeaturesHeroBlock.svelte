<script>
  import BlockSection from './BlockSection.svelte';

  const stats = [
    { label: "Positioning", value: "Hero statement|Focus" },
    { label: "Decision speed|Signal", value: "High confidence" },
    { label: "", value: "" }
  ];
</script>

<BlockSection
  title="Features Hero Block"
  nodeId="9210:945"
  width={1440}
  height={876}
  tone="dark"
  summary="A top-of-page feature narrative highlighting product differentiators."
  eyebrow="FEATURES"
  cta="Explore Features"
  {stats}
/>
