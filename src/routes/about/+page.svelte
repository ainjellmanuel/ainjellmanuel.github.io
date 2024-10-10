<script lang="ts">
  let profilePic = "jell.jpg";
  let aboutMe =
    "Hi! I’m Ainjell Jhunefel M. Manuel, a 3rd year IT student, an aspiring Frontend Developer with a passion for crafting intuitive web experiences. Throughout my journey, I’ve explored how thoughtful design can bridge the gap between technology and users, making everyday interactions simpler and more engaging. I dream of collaborating with clients across the globe, bringing their visions to life through seamless, responsive designs that captivate and engage. My work focuses on solving real-world problems through clean, user-centric interfaces, ensuring each project reflects both creativity and functionality. As I continue to grow as a frontend developer, I’m excited to connect with international clients and contribute innovative solutions to the digital landscape. Thank you for stopping by—let’s build something amazing together!";
</script>

<div class="flex flex-col justify-center items-center h-auto text-center p-5 dark:text-red-50">
  <div class="text-3xl font-bold mb-5">Get to know me better!</div>
  <img src={profilePic} alt="ainjell" class="mb-5"/>
  <p class="text-base leading-5 max-w-xl">{aboutMe}</p>
</div>
