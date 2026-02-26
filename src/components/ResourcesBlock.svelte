<script>
  import BlockSection from './BlockSection.svelte';

  const stats = [
    { label: "Content", value: "Editorial packs|Formats" },
    { label: "Reports + webinars|Cadence", value: "Weekly drops" },
    { label: "", value: "" }
  ];
</script>

<BlockSection
  title="Resources Block"
  nodeId="9210:949"
  width={1440}
  height={874}
  tone="light"
  summary="Curated research, webinars, and practical playbooks for procurement teams."
  eyebrow="RESOURCE HUB"
  cta="View Resources"
  {stats}
/>
