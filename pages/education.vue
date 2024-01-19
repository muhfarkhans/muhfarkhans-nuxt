<script setup>
useSeoMeta({
  title: "Education",
  ogTitle: "Muhammad Farkhan Syafii Site",
  description: "This is my education history page",
});
</script>

<template>
  <div class="flex flex-col min-h-screen">
    <header class="w-full px-4 py-4 mx-auto md:px-12 max-w-7xl">
      <Navbar />
    </header>
    <main class="flex-1 w-full px-4 mx-auto md:px-12 max-w-7xl">
      <h1 class="mb-10 text-5xl font-bold">Education</h1>
      <div class="mb-10">
        <h3 class="text-3xl font-semibold">Universitas Amikom Yogyakarta</h3>
        <h3 class="text-2xl">2019 - 2023</h3>
      </div>
      <div class="mb-10">
        <h3 class="text-3xl font-semibold">SMK Negeri 2 Depok Sleman</h3>
        <h3 class="text-2xl">2015 - 2019</h3>
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
