<script lang="ts">
  import { Gallery } from 'flowbite-svelte';

const images = [
  { alt: 'Academic Profiling UI', src: 'app-home.png' },
  { alt: 'Cost Control UI', src: 'cost-control-home.png' },
  { alt: 'Cost Control UI', src: 'cost-control-track.png' },
  { alt: 'Academic Profiling UI', src: 'app-crud.png' },
  { alt: 'Academic Profiling UI', src: 'app-settings.png' },
  { alt: 'GC Brochure', src: 'GC-Brochure.jpg' },
  { alt: 'Cost Control UI', src: 'cost-control-track.png' },
  { alt: 'Ecommerce App', src: 'furnistyle.png' },
];
</script>

<div class="dark:text-orange-300">
  <div class=" flex justify-center">
    <h1 class="text-4xl font-bold ">My Collection</h1>
  </div>
  <div class="flex justify-center p-5">
    <p class="text-lg font-semibold tracking-wider">These are some of my recently creations. Have a look at them and let me know if you like it.</p>
  </div>

  <div>
    <!--  Image Gallery -->
    <Gallery class="gap-4 grid-cols-2 md:grid-cols-4" items={images} />
  </div>
</div>