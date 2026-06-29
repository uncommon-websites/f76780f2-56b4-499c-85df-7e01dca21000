<script>
  import VideoCard from "$lib/components/VideoCard.svelte";
</script>

<div class="pt-32 pb-20">
  <!-- Hero Section -->
  <section class="max-w-[1400px] mx-auto px-4 md:px-8 mb-24">
    <h1 class="text-[clamp(3rem,8vw,6rem)] leading-[0.9] font-medium text-center mb-12 tracking-tight">
      Say hello to Afternoon
    </h1>
    
    <div class="w-full aspect-[16/10] bg-gray-200 rounded-2xl overflow-hidden mb-12 relative">
      <img src="/generated/image-modern-web-design-studio-workspace-with--1782759201509-0.webp" alt="Afternoon website studio workspace" class="absolute inset-0 w-full h-full object-cover opacity-90" />
    </div>

    <div class="max-w-2xl">
      <p class="text-xl md:text-2xl leading-relaxed text-gray-800">
        Built for B2B SaaS companies whose product deserves a better website. We turn unclear, overgrown sites into high-performing growth channels.
      </p>
    </div>
  </section>

  <!-- Intro Video Section -->
  <section class="max-w-[1400px] mx-auto px-4 md:px-8 mb-40">
    <div class="flex flex-col md:flex-row items-end justify-between gap-12">
      <div class="max-w-xs mb-8 md:mb-0">
        <p class="text-xs font-medium leading-relaxed text-gray-500 uppercase tracking-wide">
          Your website should work as hard as your product does. Watch how we help software companies turn their site into their strongest sales asset.
        </p>
      </div>
      <div class="w-full md:w-[400px]">
        <VideoCard 
          imageSrc="/generated/image-two-designers-collaborating-at-a-desk-re-1782759205380-1.webp" 
          alt="How Afternoon works"
          title="Our Approach"
          subtitle="Watch"
        />
      </div>
    </div>
  </section>

  <!-- Clarity Made Conversion -->
  <section class="max-w-[1000px] mx-auto px-4 mb-40">
    <div class="flex flex-col gap-8 text-[clamp(4rem,10vw,9rem)] leading-[0.8] tracking-tight font-medium">
      <div class="text-left">Clarity</div>
      <div class="text-center pl-[20%]">made</div>
      <div class="text-right pr-[10%]">conversion</div>
    </div>
  </section>

  <!-- Messaging Section -->
  <section class="max-w-[1400px] mx-auto px-4 md:px-8 mb-32">
    <div class="max-w-2xl mx-auto text-center mb-16">
      <p class="text-lg text-gray-600 leading-relaxed">
        Powered by sharp messaging strategy and a proven conversion framework, Afternoon doesn't just make your site look better — it makes your site perform better, from first visit to signed contract.
      </p>
    </div>

    <div class="grid grid-cols-1 gap-4">
      <!-- Main Image -->
      <div class="relative w-full aspect-[16/9] bg-gray-200 rounded-2xl overflow-hidden group">
        <img src="/generated/image-side-by-side-comparison-of-a-cluttered-c-1782759208567-2.webp" alt="Website transformation" class="absolute inset-0 w-full h-full object-cover" />
        <div class="absolute inset-0 bg-black/30"></div>
        <div class="absolute bottom-8 left-8 md:bottom-12 md:left-12">
          <h2 class="text-3xl md:text-5xl font-medium text-white tracking-tight">We start with your message</h2>
        </div>
        <div class="absolute top-4 left-4 px-2 py-1 bg-black/30 backdrop-blur-md rounded text-[10px] uppercase tracking-wider text-white font-medium">
          01
        </div>
      </div>

      <!-- Sub Images Row -->
      <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
        <div class="aspect-[4/3] bg-gray-200 rounded-2xl overflow-hidden relative p-8 flex items-end">
           <img src="/generated/image-designer-reviewing-b2b-saas-website-on-l-1782759211628-3.webp" alt="Messaging strategy session" class="absolute inset-0 w-full h-full object-cover opacity-30" />
           <p class="text-xs text-gray-600 max-w-xs relative z-10">
             We audit your existing site, sharpen your positioning, and restructure your content so visitors immediately understand what you do, who it's for, and why it matters. No jargon. No vague headlines. Just clarity that converts.
           </p>
           <div class="absolute top-4 left-4 text-[10px] text-gray-400 uppercase tracking-wider">Messaging that lands</div>
        </div>
        <div class="aspect-[4/3] bg-gray-200 rounded-2xl overflow-hidden relative">
           <img src="/generated/image-designer-reviewing-b2b-saas-website-on-l-1782759211628-3.webp" alt="Website before and after" class="absolute inset-0 w-full h-full object-cover" />
           <div class="absolute inset-0 bg-black/20"></div>
          <div class="absolute bottom-4 left-4 flex items-center gap-2 text-white">
             <div class="w-6 h-6 rounded-full bg-white/20 backdrop-blur-md flex items-center justify-center">
              <svg width="8" height="10" viewBox="0 0 10 12" fill="none" class="ml-0.5"><path d="M9 6L0.75 10.7631L0.75 1.23686L9 6Z" fill="currentColor"/></svg>
            </div>
            <span class="text-xs font-medium">See the transformation</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Works for any SaaS Section -->
  <section class="max-w-[1400px] mx-auto px-4 md:px-8 mb-32">
    <div class="grid grid-cols-1 gap-4">
      <!-- Main Image -->
      <div class="relative w-full aspect-[16/9] bg-gray-200 rounded-2xl overflow-hidden">
        <img src="/generated/image-multiple-saas-product-dashboards-and-int-1782759214401-4.webp" alt="B2B SaaS products across verticals" class="absolute inset-0 w-full h-full object-cover" />
        <div class="absolute inset-0 bg-black/40"></div>
        <div class="absolute inset-0 flex items-center justify-center">
          <h2 class="text-3xl md:text-5xl font-medium text-white tracking-tight text-center max-w-2xl">
            Built for SaaS,<br/>across every vertical
          </h2>
        </div>
        <div class="absolute top-4 left-4 px-2 py-1 bg-black/30 backdrop-blur-md rounded text-[10px] uppercase tracking-wider text-white font-medium">
          02
        </div>
      </div>

      <!-- Sub Images Row -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
        <div class="aspect-square md:aspect-auto md:h-64 bg-white rounded-2xl p-6 flex flex-col justify-between">
           <p class="text-[10px] uppercase tracking-wider text-gray-400">Every product is different. Every site should be too.</p>
           <p class="text-xs text-gray-600 leading-relaxed">
             We work exclusively with B2B SaaS companies, which means we understand your sales cycle, your buyer, and your product complexity. Every engagement is tailored — no templates, no shortcuts, no one-size-fits-all solutions.
           </p>
        </div>
        <div class="aspect-video md:aspect-auto bg-gray-200 rounded-2xl overflow-hidden relative">
           <img src="/generated/image-strategy-session-with-team-around-whiteb-1782759217403-5.webp" alt="Discovery and strategy session" class="absolute inset-0 w-full h-full object-cover" />
           <div class="absolute inset-0 bg-black/20"></div>
           <div class="absolute bottom-4 left-4 flex items-center gap-2 text-white">
             <div class="w-6 h-6 rounded-full bg-white/20 backdrop-blur-md flex items-center justify-center">
              <svg width="8" height="10" viewBox="0 0 10 12" fill="none" class="ml-0.5"><path d="M9 6L0.75 10.7631L0.75 1.23686L9 6Z" fill="currentColor"/></svg>
            </div>
            <span class="text-xs font-medium">01. Discovery & Strategy</span>
          </div>
        </div>
        <div class="aspect-video md:aspect-auto bg-gray-200 rounded-2xl overflow-hidden relative">
           <img src="/generated/image-designer-building-a-clean-modern-website-1782759220159-6.webp" alt="Design and build phase" class="absolute inset-0 w-full h-full object-cover" />
           <div class="absolute inset-0 bg-black/20"></div>
           <div class="absolute bottom-4 left-4 flex items-center gap-2 text-white">
             <div class="w-6 h-6 rounded-full bg-white/20 backdrop-blur-md flex items-center justify-center">
              <svg width="8" height="10" viewBox="0 0 10 12" fill="none" class="ml-0.5"><path d="M9 6L0.75 10.7631L0.75 1.23686L9 6Z" fill="currentColor"/></svg>
            </div>
            <span class="text-xs font-medium">02. Design & Build</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Results Section -->
  <section class="max-w-[1400px] mx-auto px-4 md:px-8 mb-40">
    <div class="grid grid-cols-1 gap-4">
      <!-- Main Image -->
      <div class="relative w-full aspect-[16/9] bg-gray-200 rounded-2xl overflow-hidden">
        <img src="/generated/image-analytics-dashboard-showing-rising-conve-1782759223191-7.webp" alt="Results and analytics" class="absolute inset-0 w-full h-full object-cover" />
        <div class="absolute inset-0 bg-black/40"></div>
        <div class="absolute inset-0 flex items-center justify-center">
          <h2 class="text-3xl md:text-5xl font-medium text-white tracking-tight text-center">
            Websites that keep getting better
          </h2>
        </div>
        <div class="absolute top-4 left-4 px-2 py-1 bg-black/30 backdrop-blur-md rounded text-[10px] uppercase tracking-wider text-white font-medium">
          03
        </div>
      </div>

      <!-- Sub Images Row -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
        <div class="aspect-square md:aspect-auto md:h-64 bg-white rounded-2xl p-6 flex flex-col justify-between">
           <p class="text-[10px] uppercase tracking-wider text-gray-400">We don't just launch and leave.</p>
           <p class="text-xs text-gray-600 leading-relaxed">
             After launch, we track performance, gather conversion data, and iterate on what matters. Your website grows alongside your product — always aligned with where your business is headed next.
           </p>
        </div>
        <div class="aspect-video md:aspect-auto bg-gray-200 rounded-2xl overflow-hidden relative">
           <img src="/generated/image-person-reviewing-website-performance-met-1782759225568-8.webp" alt="Conversion rate improvement" class="absolute inset-0 w-full h-full object-cover" />
           <div class="absolute inset-0 bg-black/20"></div>
           <div class="absolute bottom-4 left-4 flex items-center gap-2 text-white">
             <div class="w-6 h-6 rounded-full bg-white/20 backdrop-blur-md flex items-center justify-center">
              <svg width="8" height="10" viewBox="0 0 10 12" fill="none" class="ml-0.5"><path d="M9 6L0.75 10.7631L0.75 1.23686L9 6Z" fill="currentColor"/></svg>
            </div>
            <span class="text-xs font-medium">A. Conversion rate improvement</span>
          </div>
        </div>
        <div class="aspect-video md:aspect-auto bg-gray-200 rounded-2xl overflow-hidden relative">
           <img src="/generated/image-designer-iterating-on-website-improvemen-1782759228502-9.webp" alt="Ongoing optimization" class="absolute inset-0 w-full h-full object-cover" />
           <div class="absolute inset-0 bg-black/20"></div>
           <div class="absolute bottom-4 left-4 flex items-center gap-2 text-white">
             <div class="w-6 h-6 rounded-full bg-white/20 backdrop-blur-md flex items-center justify-center">
              <svg width="8" height="10" viewBox="0 0 10 12" fill="none" class="ml-0.5"><path d="M9 6L0.75 10.7631L0.75 1.23686L9 6Z" fill="currentColor"/></svg>
            </div>
            <span class="text-xs font-medium">B. Ongoing optimization in action</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Strategy to Structure -->
  <section class="bg-[#E3EBE6] py-32 mb-32 -mx-4 md:-mx-8 px-4 md:px-8">
    <div class="max-w-[1400px] mx-auto">
      <h2 class="text-[clamp(2.5rem,5vw,4rem)] leading-tight font-medium text-center mb-20 tracking-tight text-balance max-w-4xl mx-auto">
        From scattered pages to a clear growth channel
      </h2>

      <div class="flex flex-col items-center mb-20">
        <div class="w-full max-w-md aspect-[3/4] bg-gray-300 rounded-2xl overflow-hidden relative mb-12">
          <img src="/generated/image-structured-website-framework-document-sp-1782759231351-10.webp" alt="Afternoon's Website Clarity Framework" class="absolute inset-0 w-full h-full object-cover" />
        </div>
        
        <div class="max-w-xl text-center">
          <p class="text-lg text-gray-700 leading-relaxed">
            Our Website Clarity Framework™ helps us diagnose exactly what's holding your site back — from weak positioning to buried product value — and gives us a precise roadmap to fix it fast.
          </p>
        </div>
      </div>

      <div class="max-w-4xl mx-auto">
        <VideoCard 
          imageSrc="/generated/image-strategy-session-with-team-around-whiteb-1782759217403-5.webp" 
          alt="Website Clarity Framework Demo"
          title="The Clarity Framework in practice"
          subtitle=""
        />
        <div class="text-center mt-12 space-y-2">
          <p class="text-xs text-gray-500 leading-relaxed max-w-xs mx-auto">
            To date, we've audited and rebuilt websites for dozens of B2B SaaS companies. Each project sharpens our process further.
          </p>
          <div class="flex justify-center gap-8 pt-4 text-[10px] uppercase tracking-wider font-medium">
            <a href="#" class="border-b border-black pb-0.5">Explore Our Process</a>
            <a href="#" class="border-b border-black pb-0.5">See Case Studies</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Designed for real results -->
  <section class="max-w-[1400px] mx-auto px-4 md:px-8 mb-32">
    <div class="text-center mb-16">
      <h2 class="text-[clamp(3rem,6vw,5rem)] leading-tight font-medium mb-8 tracking-tight">
        Designed for real<br/>results
      </h2>
      
      <div class="inline-flex bg-white rounded-full p-1 border border-gray-200">
        <button class="px-4 py-1.5 rounded-full bg-black text-white text-xs font-medium">Capabilities</button>
        <button class="px-4 py-1.5 rounded-full hover:bg-gray-100 text-gray-500 text-xs font-medium transition-colors">Process</button>
        <button class="px-4 py-1.5 rounded-full hover:bg-gray-100 text-gray-500 text-xs font-medium transition-colors">Deliverables</button>
      </div>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4 mb-32">
      <!-- Card 1: Messaging -->
      <div class="aspect-square bg-[#1a1a1a] rounded-2xl overflow-hidden relative group">
        <!-- Abstract visual -->
        <div class="absolute inset-0 flex items-center justify-center">
            <div class="w-32 h-32 rounded-full bg-[#2a2a2a] border border-[#333] flex items-center justify-center">
                <div class="w-16 h-16 rounded-full bg-[#111] border border-[#222]"></div>
            </div>
        </div>
        <div class="absolute top-6 left-6 right-6">
          <h3 class="text-white text-sm font-bold mb-2">Messaging that actually sticks</h3>
          <p class="text-[10px] text-gray-400 leading-relaxed">
            We rework your positioning, headlines, and page copy so your ideal buyer immediately gets what you do and why it matters — without reading three paragraphs first.
          </p>
        </div>
      </div>

      <!-- Card 2: Conversion -->
      <div class="aspect-square bg-[#F0EFE9] rounded-2xl p-6 flex flex-col justify-between overflow-hidden relative">
         <div class="relative z-10">
            <h3 class="text-black text-sm font-bold mb-2">Conversion-focused from the start</h3>
            <p class="text-[10px] text-gray-500 leading-relaxed">
            Every section, every CTA, every page is structured to move your visitor toward the next step — a demo, a signup, or a conversation with your team.
            </p>
         </div>
         <!-- Orange abstract shape -->
         <div class="absolute -bottom-10 -right-10 w-48 h-48 bg-[#FF4500] rounded-full blur-xl opacity-80"></div>
         <div class="absolute bottom-0 right-0 w-full h-1/2 bg-gradient-to-t from-[#FF4500] to-transparent opacity-20"></div>
         <div class="w-full h-40 bg-[#FF4500] rounded-full absolute -bottom-20 left-1/2 -translate-x-1/2"></div>
      </div>

      <!-- Card 3: Close up -->
      <div class="aspect-square bg-gray-200 rounded-2xl overflow-hidden relative">
         <img src="/generated/image-close-up-of-hands-typing-on-keyboard-wit-1782759234129-11.webp" alt="Hands-on website craft" class="w-full h-full object-cover" />
      </div>
      
       <!-- Card 4: Tailored -->
      <div class="aspect-square bg-[#333] rounded-2xl overflow-hidden relative">
         <!-- CSS Art for colorful balls -->
         <div class="absolute inset-0">
            <div class="absolute top-10 left-10 w-20 h-20 rounded-full bg-yellow-400 shadow-lg"></div>
            <div class="absolute top-20 right-10 w-24 h-24 rounded-full bg-red-500 shadow-lg z-10"></div>
            <div class="absolute bottom-10 left-20 w-28 h-28 rounded-full bg-blue-500 shadow-lg"></div>
            <div class="absolute bottom-20 right-20 w-16 h-16 rounded-full bg-green-400 shadow-lg"></div>
            <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-32 h-32 rounded-full bg-white/10 backdrop-blur-md z-20"></div>
         </div>
         <div class="absolute top-6 left-6 right-6 z-30">
          <h3 class="text-white text-sm font-bold mb-2">Tailored to your product</h3>
          <p class="text-[10px] text-gray-300 leading-relaxed">
            We don't apply the same template to every client. Your site is crafted around your product's unique value, your buyers' real objections, and your team's growth goals.
          </p>
        </div>
      </div>

      <!-- Card 5: Clean and fast -->
      <div class="aspect-square bg-[#B8C6C0] rounded-2xl p-6 flex flex-col justify-between overflow-hidden relative">
         <div class="relative z-10">
            <h3 class="text-black text-sm font-bold mb-2">Clean, fast and easy to manage</h3>
            <p class="text-[10px] text-gray-700 leading-relaxed">
            We build on modern stacks your team can actually maintain. No bloated page builders, no mystery plugins — just a site that's as dependable as the product behind it.
            </p>
         </div>
         <!-- Grid texture -->
         <div class="absolute inset-0 opacity-20" style="background-image: linear-gradient(#000 1px, transparent 1px), linear-gradient(90deg, #000 1px, transparent 1px); background-size: 20px 20px;"></div>
      </div>

      <!-- Card 6: Hand touch -->
      <div class="aspect-square bg-yellow-400 rounded-2xl overflow-hidden relative">
         <img src="/generated/image-creative-designers-hand-pointing-at-a-cl-1782759236856-12.webp" alt="Collaborative design review" class="w-full h-full object-cover mix-blend-multiply opacity-80" />
         <div class="absolute inset-0 bg-yellow-400/30 mix-blend-overlay"></div>
      </div>
    </div>
    
    <!-- Repeat Tabs for visual consistency if needed or just bottom spacing -->
    <div class="flex justify-center">
       <div class="inline-flex bg-white rounded-full p-1 border border-gray-200 opacity-50 pointer-events-none">
        <button class="px-4 py-1.5 rounded-full bg-black text-white text-xs font-medium">Capabilities</button>
        <button class="px-4 py-1.5 rounded-full text-gray-500 text-xs font-medium">Process</button>
        <button class="px-4 py-1.5 rounded-full text-gray-500 text-xs font-medium">Deliverables</button>
      </div>
    </div>
  </section>

  <!-- Approaches Section -->
  <section class="bg-[#DCEBEF] py-40 -mx-4 md:-mx-8 px-4 md:px-8 flex flex-col items-center text-center">
    <div class="flex flex-col md:flex-row items-center justify-between w-full max-w-2xl mb-12 gap-8">
      <span class="text-xs font-medium text-gray-500">Afternoon wears many hats.</span>
      
      <div class="w-24 h-24 text-black">
        <!-- Flower/Icon -->
        <svg viewBox="0 0 100 100" fill="currentColor" class="w-full h-full animate-spin-slow">
          <path d="M50 20C58 20 65 27 65 35C65 43 58 50 50 50C42 50 35 43 35 35C35 27 42 20 50 20Z" />
          <path d="M50 80C42 80 35 73 35 65C35 57 42 50 50 50C58 50 65 57 65 65C65 73 58 80 50 80Z" />
          <path d="M20 50C20 42 27 35 35 35C43 35 50 42 50 50C50 58 43 65 35 65C27 65 20 58 20 50Z" />
          <path d="M80 50C80 58 73 65 65 65C57 65 50 58 50 50C50 42 57 35 65 35C73 35 80 42 80 50Z" />
        </svg>
      </div>

      <span class="text-xs font-medium text-gray-500">Which challenge should we tackle next?</span>
    </div>

    <button class="bg-black text-white px-8 py-3 rounded-full text-xs font-bold uppercase tracking-wider hover:scale-105 transition-transform">
      Tell us your biggest problem
    </button>
  </section>

  <!-- FAQ Section -->
  <section class="max-w-[800px] mx-auto px-4 py-32">
    <h3 class="text-xs font-medium text-gray-500 mb-12">Frequently asked questions</h3>
    
    <div class="space-y-4">
      {#each [
        "What does Afternoon actually do?",
        "Who is Afternoon for?",
        "How long does a typical project take?",
        "What does a project with Afternoon cost?",
        "Do you only design, or do you build as well?",
        "What happens after the website launches?"
      ] as question}
        <div class="border-b border-gray-200 pb-4 group cursor-pointer">
          <div class="flex items-center justify-between py-2">
            <span class="text-sm font-medium group-hover:text-gray-600 transition-colors">{question}</span>
            <span class="text-gray-400 group-hover:text-black transition-colors">
              <svg width="10" height="6" viewBox="0 0 10 6" fill="none" class="transform transition-transform group-hover:rotate-180">
                <path d="M1 1L5 5L9 1" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </span>
          </div>
        </div>
      {/each}
    </div>
  </section>

  <!-- Founding Clients Section -->
  <section class="max-w-[1400px] mx-auto px-4 md:px-8 mb-20">
    <div class="bg-[#111111] rounded-2xl p-12 md:p-24 text-center relative overflow-hidden">
      <div class="relative z-10 flex flex-col items-center gap-6">
        <h2 class="text-white text-xl md:text-2xl font-medium tracking-tight">
          Be one of our founding clients. <span class="text-[#FCEE4F]">Direct access. Honest pricing. Real results.</span>
        </h2>
        <button class="inline-flex items-center gap-2 px-6 py-2 rounded-full border border-white/20 text-white text-xs uppercase tracking-wider hover:bg-white/10 transition-colors">
          Start a conversation
          <svg width="10" height="10" viewBox="0 0 10 10" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M1 9L9 1M9 1H3M9 1V7" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
        </button>
      </div>
      
      <!-- Background gradient/glow -->
      <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-full h-full max-w-2xl max-h-2xl bg-gradient-to-r from-blue-900/20 to-purple-900/20 blur-3xl rounded-full pointer-events-none"></div>
    </div>
  </section>

</div>
