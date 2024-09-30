<script setup lang="ts">
useHead({
  title: "Ian Kranz | About",
  meta: [
    {
      name: "description",
      content:
        "Ian Kranz is a software engineer based in Brooklyn, NY. He graduated from Cornell University with a Bachelor's of Science in Electrical and Computer Engineering"
    }
  ]
})

useSeoMeta({
  title: "Ian Kranz | About",
  ogTitle: "Ian Kranz | About",
  description:
    "Ian Kranz is a software engineer based in Brooklyn, NY. He graduated from Cornell University with a Bachelor's of Science in Electrical and Computer Engineering",
  ogDescription:
    "Ian Kranz is a software engineer based in Brooklyn, NY. He graduated from Cornell University with a Bachelor's of Science in Electrical and Computer Engineering"
})
</script>

<template>
  <div
    style="
      width: 100%;
      max-width: 30rem;
      display: flex;
      margin-top: 2rem;
      gap: 1rem;
      align-items: center;
    "
  >
    <img src="/logo.png" style="height: 4rem" />
    <div>
      <h1 style="margin: 0rem">Ian Kranz</h1>
      <h2
        style="
          margin: 0rem;
          font-weight: 400;
          color: rgb(107 114 128);
          font-size: 1rem;
        "
      >
        Software Engineer
      </h2>
    </div>
  </div>
  <MyNav selected="about" />
  <main
    style="
      display: flex;
      flex-direction: column;
      width: 100%;
      max-width: 30rem;
      gap: 3rem;
    "
  >
    <div>
      <h1>Hi, I'm Ian</h1>
      <p>I live in Brooklyn, NY</p>
      <p>When I'm not writing code, I like to:</p>
      <ul>
        <li>
          <b>Try new restaurants</b> - I love the never ending supply of
          restaurants offered by New York City
        </li>
        <li>
          <b>Travel</b> - I like a mix of exploring new cities and experiencing
          nature
        </li>
        <li>
          <b>Watch and play tennis</b> - I'm a beginner player, but I love to
          watch the major tournaments and go to the US Open every year
        </li>
        <li><b>See movies</b> - I really like horror and SciFi films</li>
        <li>
          <b>Play games</b> - I play board games and videogames, often with
          friends
        </li>
      </ul>
    </div>
  </main>
</template>
