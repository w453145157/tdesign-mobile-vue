<template>
  <t-slider v-model="value" show-value />
</template>

<script lang="ts" setup>
import { ref } from 'vue';

const value = ref(60);
</script>
