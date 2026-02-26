<script>
  import BlockSection from './BlockSection.svelte';

  const stats = [
    { label: "Goal", value: "Pipeline creation|Primary action" },
    { label: "Book demo|Friction", value: "Low" },
    { label: "", value: "" }
  ];
</script>

<BlockSection
  title="Call-to-Action Block"
  nodeId="9210:943"
  width={1440}
  height={977}
  tone="dark"
  summary="Single conversion surface prompting demos and stakeholder follow-up."
  eyebrow="CTA"
  cta="Book Demo"
  {stats}
/>
