<script setup>
const props = defineProps({
  text: String,
});
</script>

<template>
  <button
    class="w-32 py-3 border-2 rounded-lg border-slate-200 hover:bg-slate-200 hover:text-slate-800"
  >
    {{ text }}
  </button>
</template>
