<script setup lang="ts">
import IconWindow from "../components/icons/IconWindow.vue"
useHead({
  title: "Ian Kranz | Software Engineering Projects",
  meta: [
    {
      name: "description",
      content:
        "Learn more about NYC-based software engineer Ian Kranz on this portfolio site. This site includes information about Ian's professional experience and domain of software engineering knowledge."
    }
  ]
})

useSeoMeta({
  title: "Ian Kranz | Software Engineering Projects",
  ogTitle: "Ian Kranz | Software Engineering Projects",
  description:
    "Learn more about NYC-based software engineer Ian Kranz on this portfolio site. This site includes information about Ian's professional experience and domain of software engineering knowledge.",
  ogDescription:
    "Learn more about NYC-based software engineer Ian Kranz on this portfolio site. This site includes information about Ian's professional experience and domain of software engineering knowledge."
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
  <MyNav selected="projects" />
  <main
    style="
      display: flex;
      flex-direction: column;
      width: 100%;
      max-width: 30rem;
      gap: 6rem;
    "
  >
    <div>
      <a
        href="https://dewdayte.com/"
        style="
          color: rgb(10 10 10);
          display: flex;
          align-items: center;
          gap: 0.5rem;
        "
        target="_blank"
      >
        <h1 style="margin: 0rem">Dewdayte</h1>
        <IconWindow style="height: 2rem" />
      </a>
      <h2>Intuitive task management application</h2>
      <img
        src="/dewdayte.png"
        style="
          width: 100%;
          border: 2px solid rgb(200 200 200);
          border-radius: 4px;
        "
      />
      <p>
        I built this project because I was interested in building a full stack
        application with NextJS. I chose a simple task management solution that
        fits with the way I like to prioritize To-Dos in my everyday life.
      </p>
      <a
        href="https://github.com/iankranz/dewdayte"
        style="text-decoration: none"
      >
        <div
          style="
            background-color: rgb(38 38 38);
            display: flex;
            padding: 1rem;
            border-radius: 8px;
            align-items: center;
            justify-content: center;
            gap: 1rem;
          "
        >
          <svg
            style="width: 2rem; height: 2rem"
            viewBox="0 0 98 96"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M48.854 0C21.839 0 0 22 0 49.217c0 21.756 13.993 40.172 33.405 46.69 2.427.49 3.316-1.059 3.316-2.362 0-1.141-.08-5.052-.08-9.127-13.59 2.934-16.42-5.867-16.42-5.867-2.184-5.704-5.42-7.17-5.42-7.17-4.448-3.015.324-3.015.324-3.015 4.934.326 7.523 5.052 7.523 5.052 4.367 7.496 11.404 5.378 14.235 4.074.404-3.178 1.699-5.378 3.074-6.6-10.839-1.141-22.243-5.378-22.243-24.283 0-5.378 1.94-9.778 5.014-13.2-.485-1.222-2.184-6.275.486-13.038 0 0 4.125-1.304 13.426 5.052a46.97 46.97 0 0 1 12.214-1.63c4.125 0 8.33.571 12.213 1.63 9.302-6.356 13.427-5.052 13.427-5.052 2.67 6.763.97 11.816.485 13.038 3.155 3.422 5.015 7.822 5.015 13.2 0 18.905-11.404 23.06-22.324 24.283 1.78 1.548 3.316 4.481 3.316 9.126 0 6.6-.08 11.897-.08 13.526 0 1.304.89 2.853 3.316 2.364 19.412-6.52 33.405-24.935 33.405-46.691C97.707 22 75.788 0 48.854 0z"
              fill="#fff"
            />
          </svg>
          <span style="color: white">View on GitHub</span>
        </div>
      </a>
    </div>
    <div>
      <a
        href="https://sudoku.iankranz.com"
        style="
          color: rgb(10 10 10);
          display: flex;
          align-items: center;
          gap: 0.5rem;
        "
        target="_blank"
      >
        <h1 style="margin: 0rem">Sudoku Checker</h1>
        <IconWindow style="height: 2rem" />
      </a>
      <h2>Validate a sudoku solution</h2>
      <img
        src="/sudoku.png"
        style="
          width: 100%;
          border: 2px solid rgb(200 200 200);
          border-radius: 4px;
        "
      />
      <p>
        I put this project together years ago when I was first starting to get
        into front-end development. I'm still quite proud of the simple
        interface for inputting a sudoku as well as the logic behind the
        validation. There are also some nice features like helpful animated
        error messages. This was built with plain old JavaScript, HTML, and CSS.
      </p>
      <a
        href="https://github.com/iankranz/sudoku-chkr"
        style="text-decoration: none"
      >
        <div
          style="
            background-color: rgb(38 38 38);
            display: flex;
            padding: 1rem;
            border-radius: 8px;
            align-items: center;
            justify-content: center;
            gap: 1rem;
          "
        >
          <svg
            style="width: 2rem; height: 2rem"
            viewBox="0 0 98 96"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M48.854 0C21.839 0 0 22 0 49.217c0 21.756 13.993 40.172 33.405 46.69 2.427.49 3.316-1.059 3.316-2.362 0-1.141-.08-5.052-.08-9.127-13.59 2.934-16.42-5.867-16.42-5.867-2.184-5.704-5.42-7.17-5.42-7.17-4.448-3.015.324-3.015.324-3.015 4.934.326 7.523 5.052 7.523 5.052 4.367 7.496 11.404 5.378 14.235 4.074.404-3.178 1.699-5.378 3.074-6.6-10.839-1.141-22.243-5.378-22.243-24.283 0-5.378 1.94-9.778 5.014-13.2-.485-1.222-2.184-6.275.486-13.038 0 0 4.125-1.304 13.426 5.052a46.97 46.97 0 0 1 12.214-1.63c4.125 0 8.33.571 12.213 1.63 9.302-6.356 13.427-5.052 13.427-5.052 2.67 6.763.97 11.816.485 13.038 3.155 3.422 5.015 7.822 5.015 13.2 0 18.905-11.404 23.06-22.324 24.283 1.78 1.548 3.316 4.481 3.316 9.126 0 6.6-.08 11.897-.08 13.526 0 1.304.89 2.853 3.316 2.364 19.412-6.52 33.405-24.935 33.405-46.691C97.707 22 75.788 0 48.854 0z"
              fill="#fff"
            />
          </svg>
          <span style="color: white">View on GitHub</span>
        </div>
      </a>
    </div>
    <div style="margin-bottom: 5rem">
      <a
        href="https://floorplan.iankranz.com"
        style="
          color: rgb(10 10 10);
          display: flex;
          align-items: center;
          gap: 0.5rem;
        "
        target="_blank"
      >
        <h1 style="margin: 0rem">Apartment Floor Planner</h1>
        <IconWindow style="height: 2rem" />
      </a>
      <h2>*Desktop only, ongoing</h2>
      <img
        src="/floorplanner.png"
        style="
          width: 100%;
          border: 2px solid rgb(200 200 200);
          border-radius: 4px;
        "
      />
      <p>
        The floor planner is an ongoing project, but it's one I find really
        interesting. This project is an SVG-based editor which I built from
        scratch. It's a TypeScript library that interfaces with the Browser API
        as well as a user interface built with Vue.
      </p>
    </div>
  </main>
</template>
