<script setup>
useSeoMeta({
  title: "Portofolio",
  ogTitle: "Muhammad Farkhan Syafii Site",
  description: "This is my portofolio page",
});
</script>

<template>
  <div class="flex flex-col min-h-screen">
    <header class="w-full px-4 py-4 mx-auto md:px-12 max-w-7xl">
      <Navbar />
    </header>
    <main class="flex-1 w-full px-4 mx-auto md:px-12 max-w-7xl">
      <h1 class="mb-10 text-5xl font-bold">Porto</h1>
      <div class="mb-20">
        <img class="" src="/img/porto-notes.png" alt="image-cli-notes" />
        <h5 class="text-3xl font-semibold">Rest API notes with go</h5>
      </div>

      <div class="mb-20">
        <img class="" src="/img/porto-event.png" alt="image-cli-event" />
        <h5 class="text-3xl font-semibold">Rest API event with go</h5>
      </div>

      <div class="mb-20">
        <h4 class="text-3xl font-semibold">And others.</h4>
        <h4 class="">
          Please contact me if you would like to know more about some of my
          projects.
        </h4>
      </div>
    </main>
    <footer
      class="flex flex-col justify-center h-20 mt-3 space-y-4 text-center"
    >
      <div class="w-full h-1 rounded bg-slate-800"></div>
      <p>© MuhFarkhanS 2023 💚</p>
    </footer>
  </div>
</template>
