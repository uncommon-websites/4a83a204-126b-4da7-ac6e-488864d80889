<script lang="ts">
  const images = [
    "/generated/image-elegant-custom-diamond-engagement-ring-w-1765507162389-1.webp",
    "/generated/image-stunning-custom-wedding-band-set-with-di-1765507164692-2.webp",
    "/generated/image-beautiful-custom-pendant-necklace-with-p-1765507166993-3.webp"
  ];
</script>

<section class="bg-white pb-24 overflow-hidden" id="engagement-rings">
  <div class="flex gap-4 overflow-x-auto px-6 pb-8 snap-x">
    {#each images as img}
      <div class="min-w-[80vw] md:min-w-[60vw] lg:min-w-[45vw] h-[400px] snap-center first:pl-0">
        <img src={img} alt="Custom jewelry piece" class="w-full h-full object-cover rounded-lg" />
      </div>
    {/each}
  </div>
  
  <div class="text-center mt-4">
    <p class="text-gray-500 text-sm mb-4">Custom Engagement Rings <span class="text-gray-400">Designed for You</span></p>
    <div class="flex justify-center gap-2">
      <div class="w-1.5 h-1.5 rounded-full bg-gray-800"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
    </div>
  </div>
</section>
