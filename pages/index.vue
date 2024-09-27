<script setup lang="ts">
useHead({
  title: "Ian Kranz | Software Engineering Portfolio",
  meta: [
    {
      name: "description",
      content:
        "Learn more about NYC-based software engineer Ian Kranz on this portfolio site. This site includes information about Ian's professional experience and domain of software engineering knowledge."
    }
  ]
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
  <MyNav selected="summary" />
  <main
    style="
      display: flex;
      flex-direction: column;
      width: 100%;
      max-width: 30rem;
      gap: 3rem;
    "
  >
    <div style="display: flex; flex-direction: column; gap: 1.5rem">
      <div style="display: flex; flex-direction: column; gap: 0.125rem">
        <div style="font-weight: 600">Specialization</div>
        <div>
          Front-end development with
          <a href="https://vuejs.org/" target="_blank">Vue.js</a>
        </div>
      </div>
      <ClientOnly>
        <YoeCounter />
      </ClientOnly>
      <a href="/ian-kranz-resume.pdf" target="_blank">View PDF resume</a>
    </div>
    <div>
      <h1>Overview</h1>
      <p>
        My experience is in building full-stack web applications. Much of my
        work has focused on front-end development, but I've often stepped into
        the role of back-end and database developer.
      </p>
      <p>Some of the tasks I do regularly are:</p>
      <ul>
        <li>Build and style application screens using HTML and CSS</li>
        <li>Make UIs responsive using JS/TS</li>
        <li>Write UI logic for calling APIs and manipulating data in JS/TS</li>
        <li>Create API endpoints for interacting with application data</li>
        <li>Write SQL to query and manipulate application data</li>
        <li>Write SQL to create new application data entities</li>
      </ul>
    </div>
    <div>
      <h1>Experience</h1>
      <div>
        <h2>Software Engineer @ SS&amp;C Technologies</h2>
        <h3>July 2024 - Present</h3>
        <p>
          I'm the front-end development lead for an ongoing project to modernize
          a wealth management application.
        </p>
        <p>
          In this role I mainly work with TypeScript, Vue.js, C#, .NET, and SQL
          Server.
        </p>
      </div>
      <div>
        <h2>Software Engineer @ Spatial Front Inc.</h2>
        <h3>March 2024 - July 2024</h3>
        <p>
          I was part of a contracted development team building new full-stack
          applications for the USDOT.
        </p>
        <p>
          In this role I worked with TypeScript, Angular, Node.js, AWS, and
          Postgres.
        </p>
      </div>
      <div>
        <h2>Software Engineer @ Spoak Decor</h2>
        <h3>February 2022 - September 2023</h3>
        <p>
          I was part of a small development team at a startup that built
          software tools for interior designers.
        </p>
        <p>
          The majority of my work in this role was with TypeScript, Vue.js, and
          Node.js
        </p>
        <p>
          I was layed off from this role as a result of a major reduction in
          force.
        </p>
      </div>
    </div>
    <div>
      <h1>Education</h1>
      <h2>Bachelor of Science - Cornell University</h2>
      <h3>Electrical and Computer Engineering</h3>
      <p>3.97 GPA (I worked hard for it)</p>
      <p>
        I did undergraduate research for the Cornell Robotic Personal Assistant
        Laboratory (RPAL)
      </p>
      <p>I was a Teaching Assistant for ECE 3140: Embedded Systems</p>
    </div>
    <div style="display: flex; gap: 2rem; margin-bottom: 3rem">
      <a href="https://www.linkedin.com/in/iankranz/">
        <div
          style="
            background-color: rgb(38 38 38);
            display: flex;
            padding: 1rem;
            border-radius: 8px;
          "
        >
          <img style="width: 2.25rem; height: 2rem" src="/_linkedin.png" />
        </div>
      </a>
      <a href="https://github.com/iankranz">
        <div
          style="
            background-color: rgb(38 38 38);
            display: flex;
            padding: 1rem;
            border-radius: 8px;
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
        </div>
      </a>
    </div>
  </main>
</template>
