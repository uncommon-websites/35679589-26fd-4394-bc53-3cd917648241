<script>
  const logos = [
    { name: "Salesforce", font: "font-sans font-bold" },
    { name: "HubSpot", font: "font-sans font-bold" },
    { name: "Workday", font: "font-sans font-bold" },
    { name: "ServiceNow", font: "font-sans font-bold tracking-tight" },
    { name: "Oracle", font: "font-sans font-bold" },
    { name: "SAP", font: "font-sans font-black tracking-widest" },
    { name: "Adobe", font: "font-sans font-bold" },
    { name: "Cisco", font: "font-sans font-bold tracking-tight" },
    { name: "IBM", font: "font-sans font-black tracking-widest" },
    { name: "Microsoft", font: "font-sans font-bold" },
    { name: "Atlassian", font: "font-sans font-bold italic" },
    { name: "Zendesk", font: "font-sans font-bold" },
  ];
</script>

<section class="py-16 border-b border-gray-100">
  <div class="container-custom text-center">
    <p class="text-[10px] font-bold tracking-[0.2em] text-gray-400 uppercase mb-10">
      Trusted by enterprise sales teams winning more RFPs
    </p>
    
    <div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-6 gap-x-8 gap-y-12 items-center justify-items-center opacity-60 grayscale hover:grayscale-0 transition-all duration-500">
      {#each logos as logo}
        <div class="text-xl md:text-2xl text-gray-800 flex items-center justify-center w-full">
           <!-- Placeholder for actual SVG logos -->
           <span class="{logo.font}">{logo.name}</span>
        </div>
      {/each}
    </div>
  </div>
</section>
