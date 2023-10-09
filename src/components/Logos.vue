<script setup>
import { ref } from "vue";

defineProps({
  msg: String,
});
</script>

<template>
  <body class="bg-teal-100">
    <nav class="text-center text-3xl bg-teal-400 py-4">
      <p>Halo dunia</p>
    </nav>

    <section class="">
      <p>Ini bagian text</p>
    </section>
  </body>
</template>
