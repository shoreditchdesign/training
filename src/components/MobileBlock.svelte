<script>
  import BlockSection from './BlockSection.svelte';

  const stats = [
    { label: "Viewports", value: "Device layouts|Content" },
    { label: "Compressed insights|Priority", value: "Field usage" },
    { label: "", value: "" }
  ];
</script>

<BlockSection
  title="Mobile Block"
  nodeId="9210:942"
  width={1440}
  height={1344}
  tone="dark"
  summary="Mobile-first preview of platform value for on-the-go commercial teams."
  eyebrow="MOBILE"
  cta="Open Mobile"
  {stats}
/>
