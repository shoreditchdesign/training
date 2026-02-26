<script>
  import BlockSection from './BlockSection.svelte';

  const stats = [
    { label: "Form", value: "Email capture|Frequency" },
    { label: "Digest cadence|Tone", value: "Executive brief" },
    { label: "", value: "" }
  ];
</script>

<BlockSection
  title="Newsletter Block"
  nodeId="9210:939"
  width={1440}
  height={495}
  tone="light"
  summary="Compact subscription module for fuel-market updates and guidance."
  eyebrow="NEWSLETTER"
  cta="Subscribe"
  {stats}
/>
