<script>
  import BlockSection from './BlockSection.svelte';

  const stats = [
    { label: "Cards", value: "Large format|Filter" },
    { label: "Topic grouping|Sort", value: "Recent first" },
    { label: "", value: "" }
  ];
</script>

<BlockSection
  title="Resource Listing"
  nodeId="9210:947"
  width={1440}
  height={1766}
  tone="dark"
  summary="A browsable listing of research content filtered for immediate action."
  eyebrow="LIBRARY"
  cta="Browse Library"
  {stats}
/>
