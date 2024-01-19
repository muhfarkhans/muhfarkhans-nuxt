<script setup>
useSeoMeta({
  title: "Muhammad Farkhan Syafii",
  ogTitle: "Muhammad Farkhan Syafii Site",
  description: "This is my personal site",
});
</script>

<template>
  <div class="flex flex-col min-h-screen">
    <header class="w-full px-4 py-4 mx-auto md:px-12 max-w-7xl">
      <Navbar />
    </header>
    <main class="flex-1 w-full px-4 mx-auto md:px-12 max-w-7xl">
      <div class="grid grid-cols-1 md:grid-cols-2">
        <div class="flex justify-center">
          <img
            src="/img/app-image.jpg"
            alt=""
            class="object-cover rounded-3xl"
          />
        </div>
        <div class="px-2 mt-4 md:px-6 md:mt-0">
          <h1 class="text-5xl font-bold">
            Laravel, CI, Go, Git, Postman, Notion and more...
          </h1>
          <img
            src="/img/crooked-line.svg"
            class="my-4"
            alt="crooked-line-svg"
          />
          <p>
            I love building things for the web and learning about new ideas and
            techniques for productivity and workflows.
          </p>
          <div class="flex flex-wrap gap-2 my-4">
            <a href="https://t.me/muhfarkhan" target="_blank">
              <ButtonLink text="Telegram" />
            </a>
            <a href="https://github.com/muhfarkhans" target="_blank">
              <ButtonLink text="Github" />
            </a>
            <a
              href="https://www.linkedin.com/in/muh-farkhan-syafii"
              target="_blank"
            >
              <ButtonLink text="LinkedIn" />
            </a>
          </div>
        </div>
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
