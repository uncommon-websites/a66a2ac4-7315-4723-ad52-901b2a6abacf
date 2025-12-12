<script lang="ts">
  import { page } from '$app/stores';
</script>

<nav class="bg-black text-white py-4 px-6 flex items-center justify-between sticky top-0 z-50 border-b border-gray-900">
  <div class="flex items-center gap-8">
    <a href="/" class="text-2xl font-medium tracking-tight">Redbird Flight</a>
    
    <div class="hidden md:flex items-center gap-6 text-[13px] font-medium text-gray-300">
      <a href="#" class="hover:text-white transition-colors">Simulators</a>
      <a href="#" class="hover:text-white transition-colors">TRACON</a>
      <a href="#" class="hover:text-white transition-colors">Redbird Pro</a>
      <a href="#" class="hover:text-white transition-colors">Resources</a>
      <a href="#" class="hover:text-white transition-colors">Support</a>
    </div>
  </div>

  <div class="flex items-center gap-4">
    <button class="text-gray-300 hover:text-white transition-colors">
      <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="11" cy="11" r="8"/><path d="m21 21-4.3-4.3"/></svg>
    </button>
    <a href="#" class="bg-primary-600 hover:bg-primary-700 text-white px-4 py-2 rounded-full text-[13px] font-medium transition-colors">
      Get a Quote
    </a>
  </div>
</nav>
