<script>
  import BlockSection from './BlockSection.svelte';

  const stats = [
    { label: "Scope", value: "Global price lens|Coverage" },
    { label: "Supplier reliability|Latency", value: "Live updates" },
    { label: "", value: "" }
  ];
</script>

<BlockSection
  title="Introduction Block"
  nodeId="9210:950"
  width={1440}
  height={948}
  tone="light"
  summary="Market confidence starts with transparent fuel intelligence across ports and suppliers."
  eyebrow="INTELLIGENCE"
  cta="Read Intro"
  {stats}
/>
