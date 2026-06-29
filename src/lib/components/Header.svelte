<script>
  let isMenuOpen = false;
</script>

<header class="fixed top-0 left-0 w-full z-50 bg-[#FBFBF9]/80 backdrop-blur-md transition-all duration-300">
  <div class="max-w-[1400px] mx-auto px-4 py-4 flex items-center justify-between relative">
    <!-- Left placeholder for balance if needed, or just empty -->
    <div class="w-10 hidden md:block"></div>

    <!-- Center Logo -->
    <div class="flex flex-col items-center">
      <div class="flex items-center gap-2 mb-1">
        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="text-black">
          <path fill-rule="evenodd" clip-rule="evenodd" d="M12 2C6.47715 2 2 6.47715 2 12C2 17.5228 6.47715 22 12 22C17.5228 22 22 17.5228 22 12C22 6.47715 17.5228 2 12 2ZM8 12C8 9.79086 9.79086 8 12 8C14.2091 8 16 9.79086 16 12C16 14.2091 14.2091 16 12 16C9.79086 16 8 14.2091 8 12Z" fill="currentColor"/>
        </svg>
        <span class="font-bold text-lg tracking-wide">AFTERNOON</span>
      </div>
    </div>

    <!-- Right Menu -->
    <button class="w-10 h-10 flex items-center justify-center hover:bg-gray-100 rounded-full transition-colors" aria-label="Menu">
      <div class="flex flex-col gap-1.5 items-end">
        <span class="w-6 h-0.5 bg-black"></span>
        <span class="w-6 h-0.5 bg-black"></span>
      </div>
    </button>
  </div>
  
  <div class="text-center pb-4 border-b border-gray-200/50">
    <p class="text-[10px] uppercase tracking-wider text-gray-500">Website Studio für B2B-SaaS</p>
    <p class="text-[10px] uppercase tracking-wider text-gray-400">Klareres Messaging. Mehr Wachstum.</p>
  </div>
</header>
