<script>
  import BlockSection from './BlockSection.svelte';

  const stats = [
    { label: "Matrix", value: "Outcome mapping|Clarity" },
    { label: "Role-based value|Decisioning", value: "Accelerated" },
    { label: "", value: "" }
  ];
</script>

<BlockSection
  title="Benefits Block"
  nodeId="9210:934"
  width={1440}
  height={897}
  tone="light"
  summary="Benefit matrix connecting product functionality to measurable results."
  eyebrow="BENEFITS"
  cta="Explore Matrix"
  {stats}
/>
