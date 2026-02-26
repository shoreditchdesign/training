<script>
  import BlockSection from './BlockSection.svelte';

  const stats = [
    { label: "Coverage", value: "Top questions|Depth" },
    { label: "Operational answers|Updated", value: "Monthly" },
    { label: "", value: "" }
  ];
</script>

<BlockSection
  title="Frequently Asked Block"
  nodeId="9210:948"
  width={1440}
  height={709}
  tone="dark"
  summary="Core answers for fuel rates, adjustment factors, and pricing dynamics."
  eyebrow="FAQ"
  cta="View FAQs"
  {stats}
/>
