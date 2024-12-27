<script>
  import "./app.css";
  import {
    Navbar,
    NavBrand,
    NavLi,
    NavUl,
    NavHamburger,
    DarkMode,
  } from "flowbite-svelte";
</script>

<div>
  <Navbar fluid>
    <NavBrand href="/">
      <span
        class="self-center whitespace-nowrap text-4xl font-semibold dark:text-green-500 text-green-800"
        >ECHO STATS</span
      >
    </NavBrand>
    <NavHamburger />
    <NavUl>
      <NavLi href="/">Home</NavLi>
      <NavLi href="/about">About</NavLi>
      <NavLi href="/pricing">Pricing</NavLi>
      <NavLi href="/contact">Contact</NavLi>
      <NavLi><DarkMode /></NavLi>
    </NavUl>
  </Navbar>

  <div></div>
</div>
