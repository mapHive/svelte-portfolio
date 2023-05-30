<script>
  import Header from '../components/Header.svelte';
</script>

<svelte:head>
  <title>kiranbrar - projects</title>
</svelte:head>

<div class="bg-gray-700 min-h-screen">
  <Header />
  <div class="flex flex-col justify-center items-center pt-20">
    <div
      class="tracking-wider p-4 bg-gradient-to-r from-[#5ea2ac] to-[#9ac0c7] text-transparent bg-clip-text font-bold text-6xl"
    >
      Projects
    </div>
  </div>

  <div class="w-6/12 max-w-4xl flex flex-col items-start pt-16 mx-auto">
    <div
      class="tracking-wider pb-4 bg-gradient-to-r from-[#f67878] to-[#e95b5b] text-transparent bg-clip-text font-bold text-4xl"
    >
      ByteMe Computers
    </div>
    <div class="text-2xl font-light text-white">
      Fully deployed service website built from the ground up with database
      integration and CRUD functions. Built home, about us, category, shop, and
      product detail pages with login validation for adding products as admin.
      Implementation of filtering functionality across pages, a product search
      feature, and newsletter signup.
      <br /><br />
      <div class="text-yellow-500 text-base font-medium">
        [HTML5, CSS3, Javascript, Java, RESTful API, Spring Boot, MySQL, Azure]
      </div>
      <a
        href="https://bytemefullstack.azurewebsites.net/"
        target="_blank"
        class="text-1xl text-pink-500">website</a
      >
      |
      <a
        href="https://github.com/mapHive/BytmeFullstack"
        target="_blank"
        class="text-1xl text-pink-500">github</a
      >
    </div>
  </div>

  <div class="w-6/12 max-w-4xl flex flex-col items-start pt-16 mx-auto">
    <div
      class="tracking-wider pb-4 bg-gradient-to-r from-[#f67878] to-[#e95b5b] text-transparent bg-clip-text font-bold text-4xl"
    >
      To Do App
    </div>
    <div class="text-2xl font-light text-white">
      A straightforward to do app using with user authentication using a
      realtime database. The user is able sign in, create a todo, update it, and
      delete when completed.
      <br /><br />
      <div class="text-yellow-500 text-base font-medium">
        [React.js, SASS, Firebase]
      </div>
      <a
        href="https://react-todo-firebase-theta.vercel.app/"
        target="_blank"
        class="text-1xl text-pink-500">website</a
      >
      |
      <a
        href="https://github.com/mapHive/react-todo-firebase"
        target="_blank"
        class="text-1xl text-pink-500">github</a
      >
    </div>
  </div>

  <div class="w-6/12 max-w-4xl flex flex-col items-start pt-16 pb-40 mx-auto">
    <div
      class="tracking-wider pb-4 bg-gradient-to-r from-[#f67878] to-[#e95b5b] text-transparent bg-clip-text font-bold text-4xl"
    >
      Chat App
    </div>
    <div class="text-2xl font-light text-white">
      Simple realtime chat app using serverless functions and consuming third
      party APIs. Let’s users engage in a back and forth dialog.
      <br /><br />
      <!-- <div class="text-sm">
        Note: To get the desired experience, open two instances of the website
        in seperate tabs. For best effect, have both the tabs viewable side by
        side to see the exchange occur.
      </div>
      <br /> -->
      <div class="text-yellow-500 text-base font-medium">
        [Next.js, Ably, Vercel]
      </div>
      <a
        href="https://realtime-chat-app-drab-rho.vercel.app/"
        target="_blank"
        class="text-1xl text-pink-500">website</a
      >
      |
      <a
        href="https://github.com/mapHive/realtime-chat-app"
        target="_blank"
        class="text-1xl text-pink-500">github</a
      >
    </div>
  </div>
</div>
