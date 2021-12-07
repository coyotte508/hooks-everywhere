<script setup lang="ts">
import { ref } from "vue";
import { useIntervalFn } from "@vueuse/core";

const time = ref(Date.now());

useIntervalFn(() => time.value = Date.now(), 1000);

</script>

<template>
  {{new Date(time)}}
</template>