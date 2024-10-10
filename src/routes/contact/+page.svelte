<script>
  // Importing social media icons from flowbite-svelte-icons
  import GithubSolid from "flowbite-svelte-icons/GithubSolid.svelte";
  import FacebookSolid from "flowbite-svelte-icons/FacebookSolid.svelte";
  import LinkedinSolid from "flowbite-svelte-icons/LinkedinSolid.svelte";
  // Profile picture source
  
  // Define the social links (optional: customize the links)
  let socialLinks = [
    { component: FacebookSolid, link: 'https://www.facebook.com/unknown.name.mousse/' },
    { component: GithubSolid, link: 'https://github.com/ainjellmanuel' },
    { component: LinkedinSolid, link: 'https://www.linkedin.com/in/ainjell-jhunefel-manuel-3b286a268/' },
  ];
</script>

<div class="flex flex-col justify-center items-center text-center dark:text-red-50">

  <div class="text-3xl font-bold mb-5">Connect with me</div>

  <!-- Social Media Icons -->
  <div class="flex justify-between w-20">
    {#each socialLinks as social}
      <a href={social.link} target="_blank" rel="noopener noreferrer" class="cursor-pointer h-24">
        <svelte:component this={social.component} />
      </a>
    {/each}
  </div>
</div>
