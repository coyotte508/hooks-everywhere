<script setup lang="ts">
import { watch } from "vue";
import { useInterval, useTimeAgo } from "@vueuse/core";

const christmas = new Date("2021-12-25");
const toChristmas = useTimeAgo(christmas);

const {counter, pause} = useInterval(400, {controls: true});

watch(counter, () => {
  if (Date.now() > christmas.getTime()) {
    pause();
    alert("C'est Noël! 🎅");
  }
});

</script>

<template>
  Chistmas is {{toChristmas}} {{".".repeat(counter % 4)}}
</template>