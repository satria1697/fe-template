<script setup lang="ts">
import { useCounterStore } from '../stores/counter'

const counter = useCounterStore()
</script>

<template>
  <p>Hello</p>
  <button type="button" @click="counter.increment">
    Count is {{ counter.count }}
  </button>
</template>
