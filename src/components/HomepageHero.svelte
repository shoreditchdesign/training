<script>
  import BlockSection from './BlockSection.svelte';

  const stats = [
    { label: "Intent", value: "Top-of-funnel narrative|Action" },
    { label: "Primary CTA|Above-fold", value: "Focused" },
    { label: "", value: "" }
  ];
</script>

<BlockSection
  title="Homepage Hero"
  nodeId="9210:932"
  width={1440}
  height={951}
  tone="dark"
  summary="Primary hero setting the value proposition and conversion path."
  eyebrow="HOMEPAGE"
  cta="Start Demo"
  {stats}
/>
