<script setup>
useSeoMeta({
  title: "Contact",
  ogTitle: "Muhammad Farkhan Syafii Site",
  description: "This is my contact page",
});
</script>

<template>
  <div class="flex flex-col min-h-screen">
    <header class="w-full px-4 py-4 mx-auto md:px-12 max-w-7xl">
      <Navbar />
    </header>
    <main class="flex-1 w-full px-4 mx-auto md:px-12 max-w-7xl">
      <h1 class="mb-10 text-5xl font-bold">Contact</h1>
      <p class="mb-4">
        Get at me on
        <a
          class="font-bold hover:text-blue-500"
          href="https://t.me/Muhfarkhan"
          target="_blank"
          >Telegram</a
        >,
        <a
          class="font-bold hover:text-blue-500"
          href="https://github.com/muhfarkhans"
          target="_blank"
          >GitHub</a
        >, and
        <a
          class="font-bold hover:text-blue-500"
          href="https://www.linkedin.com/in/muh-farkhan-syafii"
          target="_blank"
          >LinkedIn</a
        >
        . Or send me an email.
      </p>
      <form
        action="mailto:farhanmuh.dev@gmail.com"
        method="post"
        enctype="text/plain"
      >
        <div class="grid grid-cols-1 gap-4 md:grid-cols-2">
          <div class="">
            <label for="name" class="block">Your Name</label>
            <input
              class="w-full h-10 pl-2 text-lg rounded text-slate-900"
              type="text"
              name="name"
              required
            />
          </div>
          <div class="">
            <label for="name" class="block">Your Email</label>
            <input
              class="w-full h-10 pl-2 text-lg rounded text-slate-900"
              type="text"
              name="name"
              required
            />
          </div>
        </div>
        <div class="my-4">
          <label for="name" class="block">Your Message</label>
          <textarea
            rows="5"
            class="w-full pl-2 text-lg rounded text-slate-900"
            type="text"
            name="name"
            required
          ></textarea>
        </div>
        <div class="">
          <button
            class="w-32 py-3 border-2 rounded-lg border-slate-200 hover:bg-slate-200 hover:text-slate-800"
          >
            Send
          </button>
        </div>
      </form>
    </main>
    <footer
      class="flex flex-col justify-center h-20 mt-3 space-y-4 text-center"
    >
      <div class="w-full h-1 rounded bg-slate-800"></div>
      <p>© MuhFarkhanS 2023 💚</p>
    </footer>
  </div>
</template>
