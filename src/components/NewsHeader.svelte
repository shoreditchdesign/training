<script>
  import BlockSection from './BlockSection.svelte';

  const stats = [
    { label: "Module", value: "Header + intro|Action" },
    { label: "Navigate content|Spacing", value: "Editorial" },
    { label: "", value: "" }
  ];
</script>

<BlockSection
  title="News Header"
  nodeId="9210:938"
  width={1440}
  height={446}
  tone="light"
  summary="Section heading and entry point to editorial/news experiences."
  eyebrow="NEWS"
  cta="Read News"
  {stats}
/>
