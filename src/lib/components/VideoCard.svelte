<script>
  export let title = "";
  export let subtitle = "";
  export let videoSrc = "";
  export let imageSrc = "";
  export let alt = "";
</script>

<div class="relative group cursor-pointer overflow-hidden rounded-xl bg-gray-200">
  {#if imageSrc}
    <img src={imageSrc} {alt} class="w-full h-full object-cover aspect-video transition-transform duration-700 group-hover:scale-105" />
  {:else}
    <div class="w-full h-full aspect-video bg-gray-300 flex items-center justify-center text-gray-500">
      {alt || 'Website Vorschau'}
    </div>
  {/if}
  
  <div class="absolute inset-0 bg-black/10 group-hover:bg-black/20 transition-colors"></div>
  
  <div class="absolute bottom-4 left-4 flex items-center gap-2 text-white">
    <div class="w-8 h-8 rounded-full bg-white/20 backdrop-blur-md flex items-center justify-center">
      <svg width="10" height="12" viewBox="0 0 10 12" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M9 6L0.75 10.7631L0.75 1.23686L9 6Z" fill="currentColor"/>
      </svg>
    </div>
    {#if title}
      <span class="text-sm font-medium">{title}</span>
    {/if}
  </div>
  
  {#if subtitle}
    <div class="absolute top-4 left-4 px-2 py-1 bg-black/30 backdrop-blur-md rounded text-[10px] uppercase tracking-wider text-white font-medium">
      {subtitle}
    </div>
  {/if}
</div>
