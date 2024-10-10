<script>
  import { DarkMode } from "flowbite-svelte";
  import "../app.css";
  
  import {
    Navbar,
    NavBrand,
    NavLi,
    NavUl,
    NavHamburger,
  } from "flowbite-svelte";
  
</script>

<svelte:head>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link
    rel="preconnect"
    href="https://fonts.gstatic.com"
    crossorigin="anonymous"
  />
  <link
    href="https://fonts.googleapis.com/css2?family=Quicksand:wght@300..700&display=swap"
    rel="stylesheet"
  />
</svelte:head>

<Navbar class="bg-[#FCFAEE] dark:bg-[#001F3F]">
  <DarkMode />
  <NavHamburger class="bg-[#FCFAEE] dark:bg-[#001F3F]"/>
  <NavUl class="bg-[#FCFAEE] dark:bg-[#001F3F]">
    <NavLi href="/">Home</NavLi>
    <NavLi href="/about">About</NavLi>
    <NavLi href="/portfolio">Portfolio</NavLi>
    <NavLi href="/contact">Contact</NavLi>
  </NavUl>
</Navbar>

<main class="bg-[#FCFAEE] p-8 min-h-screen min-w-screen flex flex-col justify-center items-center dark:bg-[#001F3F]">
  <slot></slot>
</main>
