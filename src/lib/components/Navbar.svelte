<script lang="ts">
  import { page } from '$app/stores';
</script>

<nav class="bg-black text-white py-4 px-6 flex items-center justify-between sticky top-0 z-50 border-b border-gray-900">
  <div class="flex items-center gap-8">
    <a href="/" class="text-2xl font-medium tracking-tight">Town Jewelers</a>
    
    <div class="hidden md:flex items-center gap-6 text-[13px] font-medium text-gray-300">
      <a href="#custom-design" class="hover:text-white transition-colors">Custom Design</a>
      <a href="#engagement-rings" class="hover:text-white transition-colors">Engagement Rings</a>
      <a href="#services" class="hover:text-white transition-colors">Services</a>
      <a href="#about" class="hover:text-white transition-colors">About</a>
      <a href="#contact" class="hover:text-white transition-colors">Visit Us</a>
    </div>
  </div>

  <div class="flex items-center gap-4">
    <a href="tel:+13019078888" class="text-gray-300 hover:text-white transition-colors text-[13px]">
      (301) 907-8888
    </a>
    <a href="#consultation" class="bg-primary-600 hover:bg-primary-700 text-white px-4 py-2 rounded-full text-[13px] font-medium transition-colors">
      Book Consultation
    </a>
  </div>
</nav>
