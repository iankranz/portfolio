<script lang="ts" setup>
import { ref, computed } from "vue"
import { differenceInSeconds, interval, intervalToDuration } from "date-fns"

const SECONDS_PER_YEAR = 31536000

const twoYears = new Date("2024-05-01")

const now = ref<Date>(new Date())

const yearsDecimal = computed(() => {
  const since = differenceInSeconds(now.value, twoYears)
  return (2 + since / SECONDS_PER_YEAR).toFixed(7)
})

const yearsSplit = computed(() => {
  const since = interval(twoYears, now.value)
  const duration = intervalToDuration(since)
  return `${2 + (duration.years ?? 0)}yr ${duration.months ?? 0}mo ${
    duration.days ?? 0
  }d ${duration.hours ?? 0}hr ${duration.minutes ?? 0}min ${
    duration.seconds ?? 0
  }sec`
})

setInterval(() => {
  now.value = new Date()
}, 1000)
</script>

<template>
  <div style="display: flex; flex-direction: column; gap: 0.125rem">
    <div style="font-weight: 600">Years of Experience</div>
    <div>{{ yearsDecimal }} ({{ yearsSplit }})</div>
  </div>
</template>
