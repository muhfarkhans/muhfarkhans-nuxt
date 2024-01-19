<script setup>
const route = useRoute();
const props = defineProps({
  current: String,
});

const routes = ref([
  { text: "Home", to: "/" },
  { text: "About", to: "/about" },
  { text: "Porto", to: "/porto" },
  { text: "Education", to: "/education" },
  { text: "Experience", to: "/experience" },
  { text: "Contact", to: "/contact" },
]);
</script>

<template>
  <nav class="grid items-center grid-cols-1 my-5 md:grid-cols-3">
    <NuxtLink to="/"
      ><h3 class="inline-block text-3xl font-bold">MuhFarkhanS</h3></NuxtLink
    >
    <div class="flex flex-wrap justify-between flex-1 col-span-2 gap-1">
      <NuxtLink v-for="_route in routes" :to="_route.to"
        ><h3 class="inline-block font-bold">
          {{ _route.text }}
          <img
            v-if="_route.to == route.path"
            src="/img/dot-blue.svg"
            alt="dot-blue"
            class="absolute inline"
          /></h3
      ></NuxtLink>
      <NuxtLink to="/notes">
        <button class="hidden px-2 rounded bg-slate-50">
          <h3 class="inline-block font-bold text-slate-800">
            Notes<img
              v-if="'/notes' == route.path"
              src="/img/dot-blue.svg"
              alt="dot-blue"
              class="absolute inline"
            />
          </h3>
        </button>
      </NuxtLink>
    </div>
  </nav>
</template>
