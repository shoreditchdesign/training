<script>
  import BlockSection from './BlockSection.svelte';

  const stats = [
    { label: "Quotes", value: "Customer voice|Use case" },
    { label: "Commercial teams|Credibility", value: "High" },
    { label: "", value: "" }
  ];
</script>

<BlockSection
  title="Testimonial Block"
  nodeId="9210:935"
  width={1440}
  height={870}
  tone="dark"
  summary="Proof points and customer voice around confidence and execution speed."
  eyebrow="TRUST"
  cta="Read Testimonials"
  {stats}
/>
