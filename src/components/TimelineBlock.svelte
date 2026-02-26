<script>
  import BlockSection from './BlockSection.svelte';

  const stats = [
    { label: "Structure", value: "Sequenced steps|Milestones" },
    { label: "Decision checkpoints|Flow", value: "End-to-end" },
    { label: "", value: "" }
  ];
</script>

<BlockSection
  title="Timeline Block"
  nodeId="9210:941"
  width={1440}
  height={978}
  tone="dark"
  summary="Chronological journey from market signal to procurement decision."
  eyebrow="TIMELINE"
  cta="View Timeline"
  {stats}
/>
