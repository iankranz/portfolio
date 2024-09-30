<script lang="ts" setup>
import IconDocument from "./icons/IconDocument.vue"
import IconUser from "./icons/IconUser.vue"
import IconCode from "./icons/IconCode.vue"
defineProps<{
  selected: "summary" | "about" | "projects"
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
          padding: 1rem;
          display: flex;
          flex-direction: column;
          align-items: center;
          justify-content: center;
          cursor: pointer;
          font-weight: 600;
        "
        :class="selected === 'summary' ? 'selected' : 'unselected'"
      >
        <IconDocument style="height: 1.25rem" />
        Summary
      </div>
    </NuxtLink>
    <NuxtLink style="text-decoration: none; flex: 1" to="about">
      <div
        style="
          flex: 1;
          border-radius: 4px;
          padding: 1rem;
          display: flex;
          flex-direction: column;
          align-items: center;
          justify-content: center;
          cursor: pointer;
          font-weight: 600;
        "
        :class="selected === 'about' ? 'selected' : 'unselected'"
      >
        <IconUser style="height: 1.25rem" />
        About
      </div>
    </NuxtLink>
    <NuxtLink style="text-decoration: none; flex: 1" to="projects">
      <div
        style="
          flex: 1;
          border-radius: 4px;
          padding: 1rem;
          display: flex;
          flex-direction: column;
          align-items: center;
          justify-content: center;
          cursor: pointer;
          font-weight: 600;
        "
        :class="selected === 'projects' ? 'selected' : 'unselected'"
      >
        <IconCode style="height: 1.25rem" />
        Projects
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
