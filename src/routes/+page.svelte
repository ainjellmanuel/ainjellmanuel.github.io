<script lang="ts">
  import ArrowRightOutline from "flowbite-svelte-icons/ArrowRightOutline.svelte";
</script>

<div class="w-full max-w-2xl grid md:grid-cols-2">
  <div class="content-center">
    <img src="ainjell.jpg" alt="ainjell" class="w-full h-auto" />
  </div>
  <div class="flex flex-col p-3 justify-center dark:text-red-50">
    <h1 class="text-2xl font-semibold tracking-wider mb-6">Hello there! I'm <span class="text-red-500 dark:text-sky-600">Ainjell</span>!</h1>
    <p>
      A 3rd-year IT student and an aspiring Frontend Developer with a passion
      for creating clean, functional, and visually engaging websites. With a
      love for designing intuitive user interfaces, I specialize in using
      Angular, Svelte, and Tailwind CSS to bring web applications to life.
      Explore my journey and projects as I continue to hone my skills and craft
      digital experiences!
    </p>
    <a href="/about"
      ><button type="button" class="w-fit mt-5 mb-2 p-3 rounded-lg text-sm bg-[#384B70] text-white"
        >Know more about me
        <ArrowRightOutline class="inline-block"/>
      </button></a
    >
    <a href="/portfolio"
      ><button type="button" class="text-sm p-3 rounded-lg bg-[#507687] text-white"
        >View my projects
        <ArrowRightOutline class="inline-block"/>
      </button></a
    >
  </div>
</div>
