<script>
  import BlockSection from './BlockSection.svelte';

  const stats = [
    { label: "Metrics", value: "High-signal KPIs|Format" },
    { label: "Carded stats|Comparisons", value: "Instant" },
    { label: "", value: "" }
  ];
</script>

<BlockSection
  title="Stats Block"
  nodeId="9210:936"
  width={1440}
  height={689}
  tone="light"
  summary="Metric-first block surfacing benchmark and performance highlights."
  eyebrow="STATS"
  cta="View Metrics"
  {stats}
/>
