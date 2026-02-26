<script>
  import BlockSection from './BlockSection.svelte';

  const stats = [
    { label: "Depth", value: "Multi-section canvas|Coverage" },
    { label: "Core modules|Length", value: "Extended" },
    { label: "", value: "" }
  ];
</script>

<BlockSection
  title="Features Block"
  nodeId="9210:933"
  width={1440}
  height={2344}
  tone="dark"
  summary="Long-form feature composition with multiple capability sections."
  eyebrow="FEATURE STACK"
  cta="Dive In"
  {stats}
/>
