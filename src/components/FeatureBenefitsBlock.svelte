<script>
  import BlockSection from './BlockSection.svelte';

  const stats = [
    { label: "Outcomes", value: "Risk reduction|Impact" },
    { label: "P&L clarity|Adoption", value: "Cross-team" },
    { label: "", value: "" }
  ];
</script>

<BlockSection
  title="Feature Benefits Block"
  nodeId="9210:946"
  width={1440}
  height={873}
  tone="dark"
  summary="Benefits mapped directly to commercial outcomes and reduced risk."
  eyebrow="VALUE"
  cta="See Benefits"
  {stats}
/>
