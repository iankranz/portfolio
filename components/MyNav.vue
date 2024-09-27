<script lang="ts" setup>
defineProps<{
  selected: "summary" | "about"
}>()
</script>

<template>
  <nav
    style="
      width: 100%;
      display: flex;
      justify-content: space-between;
      max-width: 30rem;
      background-color: rgb(245 245 245);
      padding: 0.5rem;
      border-radius: 4px;
      gap: 0.5rem;
    "
  >
    <NuxtLink style="text-decoration: none; flex: 1" to="/">
      <div
        style="
          flex: 1;
          border-radius: 4px;
          height: 3rem;
          display: flex;
          align-items: center;
          justify-content: center;
          cursor: pointer;
          font-weight: 600;
        "
        :class="selected === 'summary' ? 'selected' : 'unselected'"
      >
        Summary
      </div>
    </NuxtLink>
    <NuxtLink style="text-decoration: none; flex: 1" to="about">
      <div
        style="
          flex: 1;
          border-radius: 4px;
          height: 3rem;
          display: flex;
          align-items: center;
          justify-content: center;
          cursor: pointer;
          font-weight: 600;
        "
        :class="selected === 'about' ? 'selected' : 'unselected'"
      >
        About
      </div>
    </NuxtLink>
  </nav>
</template>

<style scoped>
.selected {
  background-color: rgb(38 38 38);
  color: white;
}
.unselected {
  background-color: transparent;
  color: rgb(10 10 10);
}
</style>
