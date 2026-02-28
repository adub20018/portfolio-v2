<template>
  <div class="card content">
    <div class="section">
      <h2>About Me</h2>
      <div class="feature-divider" />
      <p>
        Lorem Ipsum is the standard dummy text of the printing and publishing
        industry, used since the 1500s as placeholder text in design and web
        development. It features a natural-looking distribution of letters that
        mimics readable English, allowing designers to focus on layout,
        typography, and visual form without distracting content
      </p>
    </div>
    <div class="section">
      <h2>Projects</h2>
      <div class="feature-divider" />
      <p>Here is a list of projects I have worked on</p>
      <div class="projects">
        <div class="project">
          <img
            src="../assets/projects/unmanic-metrics-screenshot.png"
            class="project-img"
          />
          <h3 class="project-title">Unmanic Metrics</h3>
          <p class="project-description">
            Premium dashboard to view user metrics for the open source project
            Unmanic
          </p>
          <div class="tags">
            <p>Vue.js</p>
            <p>JavaScript</p>
            <p>LogQL</p>
          </div>
        </div>
        <div class="project">
          <img
            src="../assets/projects/decentralaw-screenshot.png"
            class="project-img"
          />
          <h3 class="project-title">Decentralawyer Website</h3>
          <p class="project-description">
            Developed and co-designed a responsive website for a crypto law firm
          </p>
          <div class="tags">
            <p>Astro</p>
            <p>CSS</p>
            <p>JavaScript</p>
          </div>
        </div>
        <div class="project">
          <img src="../assets/projects/SpaceCraft.png" class="project-img" />
          <h3 class="project-title">SpaceCraft</h3>
          <p class="project-description">
            Space themed incremental mobile game, created with Java/LibGDX
            framework
          </p>
          <div class="tags">
            <p>Android</p>
            <p>Java</p>
            <p>LibGDX</p>
          </div>
        </div>
        <div class="project">
          <img src="../assets/projects/flex-website.png" class="project-img" />
          <h3 class="project-title">Flex Engineering Website</h3>
          <p class="project-description">
            Improved the design of an existing website to modernise and tailor
            to client's needs
          </p>
          <div class="tags">
            <p>Astro</p>
            <p>CSS</p>
            <p>JavaScript</p>
          </div>
        </div>
        <div class="project">
          <img
            src="../assets/projects/flex-website-image.png"
            class="project-img"
          />
          <h3 class="project-title">SpaceCraft</h3>
          <p class="project-description">
            Lorem Ipsum is the standard dummy text of the printing and
            publishing industry, used since 1500
          </p>
          <div class="tags">
            <p>Android</p>
            <p>Java</p>
            <p>LibGDX</p>
          </div>
        </div>
        <div class="project">
          <img
            src="../assets/projects/4ozstudio-screenshot.png"
            class="project-img"
          />
          <h3 class="project-title">4ozStudio</h3>
          <p class="project-description">
            Created a website for a game studio, worked closely with client to
            match their creative direction
          </p>
          <div class="tags">
            <p>Android</p>
            <p>Java</p>
            <p>LibGDX</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.content {
  width: 100%;
  max-width: 1024px;
  height: fit-content;
}

.projects {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
}
.project {
  max-width: 250px;
  margin-top: 1.5rem;
  padding: 0.8rem;
  transition: ease-in-out 0.2s;
}
.project:hover {
  background-color: var(--color-background-transparent);
  padding: 0.8rem;
  border-radius: 1rem;
}
.project-img {
  width: 100%;
  border-radius: 6px;
}
.project-title {
  margin-bottom: 0.2rem;
}
.project-description {
  font-size: 14px;
  color: var(--color-text-passive);
}
.tags {
  display: flex;
  gap: 0.5rem;
  margin-top: 0.5rem;
}
.tags p {
  border-radius: 8px;
  padding: 0.2rem 0.5rem;
  background-color: var(--color-feature-transparent);
  color: var(--color-feature);
  width: fit-content;
  line-height: 15px;
}
</style>
