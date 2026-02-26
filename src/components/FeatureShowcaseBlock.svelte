<script>
  import BlockSection from './BlockSection.svelte';

  const stats = [
    { label: "Layout", value: "Card comparison|Modules" },
    { label: "Feature lanes|Readability", value: "High" },
    { label: "", value: "" }
  ];
</script>

<BlockSection
  title="Feature Showcase Block"
  nodeId="9210:944"
  width={1440}
  height={800}
  tone="dark"
  summary="Feature detail cards designed to compare capabilities side by side."
  eyebrow="SHOWCASE"
  cta="Open Showcase"
  {stats}
/>
