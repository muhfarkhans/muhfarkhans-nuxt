<script setup>
useSeoMeta({
  title: "About",
  ogTitle: "Muhammad Farkhan Syafii Site",
  description: "This is a page about me",
});
</script>

<template>
  <div class="flex flex-col min-h-screen">
    <header class="w-full px-4 py-4 mx-auto md:px-12 max-w-7xl">
      <Navbar />
    </header>
    <main class="flex-1 w-full px-4 mx-auto md:px-12 max-w-7xl">
      <h1 class="mb-10 text-5xl font-bold">About</h1>
      <h2 class="text-2xl font-semibold">Muhammad Farkhan Syafii</h2>
      <h2 class="text-2xl font-semibold">Bantul, 14 Maret 2000</h2>
      <h2 class="text-2xl font-semibold">
        Daerah Istimewa Yogyakarta, Indonesia
      </h2>
      <p class="my-10">
        Hi i'm Farkhan, a Backend Developer with five years of experience,
        passionate about continually enhancing my expertise in application
        development, with a focus on PHP, Javascript, and Golang.
      </p>
      <a href="/pdf/CV-MuhammadFarkhanSyafii.pdf" download>
        <button
          class="w-32 py-3 border-2 rounded-lg border-slate-200 hover:bg-slate-200 hover:text-slate-800"
        >
          Download CV
        </button>
      </a>
    </main>
    <footer
      class="flex flex-col justify-center h-20 mt-3 space-y-4 text-center"
    >
      <div class="w-full h-1 rounded bg-slate-800"></div>
      <p>© MuhFarkhanS 2023 💚</p>
    </footer>
  </div>
</template>
