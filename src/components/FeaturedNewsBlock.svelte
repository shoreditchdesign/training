<script>
  import BlockSection from './BlockSection.svelte';

  const stats = [
    { label: "Stories", value: "Spotlight cards|Priority" },
    { label: "Top items|Consumption", value: "Quick scan" },
    { label: "", value: "" }
  ];
</script>

<BlockSection
  title="Featured News Block"
  nodeId="9210:937"
  width={1440}
  height={1367}
  tone="light"
  summary="Promoted news stories and insight highlights for fast scanning."
  eyebrow="FEATURED"
  cta="Open Stories"
  {stats}
/>
