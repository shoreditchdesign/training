<script>
  import BlockSection from './BlockSection.svelte';

  const stats = [
    { label: 'Contact', value: 'hello@engine.online' },
    { label: 'Coverage', value: 'Global bunkering ports' },
    { label: 'Updated', value: 'Live market feed' }
  ];
</script>

<BlockSection
  title="Footer"
  nodeId="footer:generated"
  width={1440}
  height={420}
  tone="dark"
  summary="Footer area for contact, product links, and subscription actions."
  eyebrow="FOOTER"
  cta="Contact Sales"
  {stats}
/>
