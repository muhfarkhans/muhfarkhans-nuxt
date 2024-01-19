<script setup>
useHead({
  title: "Notes",
});
</script>

<template>
  <div class="flex flex-col min-h-screen">
    <header class="w-full px-4 py-4 mx-auto md:px-12 max-w-7xl">
      <Navbar />
    </header>
    <main class="flex-1 w-full px-4 mx-auto md:px-12 max-w-7xl">
      <h1 class="mb-10 text-5xl font-bold">Notes</h1>
      <h2 class="text-2xl font-semibold">
        Kindly forward your notes, and I will promptly respond to them,
        addressing any questions or concerns you may have. :D
      </h2>
    </main>
    <footer
      class="flex flex-col justify-center h-20 mt-3 space-y-4 text-center"
    >
      <div class="w-full h-1 rounded bg-slate-800"></div>
      <p>© MuhFarkhanS 2023 💚</p>
    </footer>
  </div>
</template>
