<script>
  import Footer from '../components/Footer.svelte';
  import Socials from '../components/Socials.svelte';
  import Header from '../components/Header.svelte';
</script>

<svelte:head>
  <title>kiranbrar - home</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Exo:wght@800&family=Maven+Pro:wght@900&display=swap');
  </style>
</svelte:head>

<div class="bg-gray-700 h-screen overflow-hidden">
  <Header />
  <div class="flex flex-col justify-center items-center h-full pb-32">
    <div
      class="font-manual text-center font-extrabold tracking-wider text-8xl bg-gradient-to-r from-[#f67878] to-[#e95b5b] text-transparent bg-clip-text"
    >
      kiran brar
    </div>
    <div class="text-md pt-4 text-blue-200">
      ProtoCoder | Audiophile | Technophile
    </div>
    <Socials />
    <Footer />
  </div>
</div>
