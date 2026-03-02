<template>
  <div class="card content">
    <div class="section">
      <h2>About Me</h2>
      <div class="feature-divider" />
      <p>
        I started out freelancing as a web designer/developer, working directly
        with clients to turn ideas into real, usable products. Over the last few
        years that's grown into more serious software work, including my first
        developer internship, contributing to open-source projects, and working
        on a Microsoft-sponsored AI capstone project.
        <br /><br />
        I'm now looking to step into a full-time software development role where
        I can further refine my skills. If you are looking for a software
        developer, please get in touch!
      </p>
    </div>
    <div class="section">
      <h2>My Work</h2>
      <div class="feature-divider" />
      <p>Here is a collection of my paid work</p>
      <div class="projects">
        <a class="project" href="https://central.unmanic.app/" target="_blank">
          <img
            src="../assets/projects/unmanic-metrics-screenshot.png"
            class="project-img"
          />
          <h3 class="project-title">Unmanic Central</h3>
          <p class="project-description">
            Premium dashboard for users to view metrics for the open source
            project Unmanic
          </p>
          <div class="tags">
            <p>Vue.js</p>
            <p>JavaScript</p>
            <p>LogQL</p>
          </div>
        </a>

        <a class="project" href="https://flexengineering.co.nz" target="_blank">
          <img src="../assets/projects/flex-website.png" class="project-img" />
          <h3 class="project-title">Flex Engineering Website</h3>
          <p class="project-description">
            Improved the design of an existing website to modernise and tailor
            to client's needs
          </p>
          <div class="tags">
            <p>WordPress</p>
            <p>CMS</p>
            <p>JavaScript</p>
          </div>
        </a>

        <a class="project" href="https://4ozstudio.com" target="_blank">
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
            <p>Astro</p>
            <p>JavaScript</p>
            <p>CSS</p>
          </div>
        </a>
        <a class="project" href="https://decentralaw.ai" target="_blank">
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
            <p>JavaScript</p>
            <p>CSS</p>
          </div>
        </a>
      </div>
    </div>
    <div class="section">
      <h2>My Projects</h2>
      <div class="feature-divider" />
      <div class="projects">
        <a
          class="project"
          href="https://github.com/ManawatuCoder/AIConvenienceAPI"
          target="_blank"
        >
          <img
            src="../assets/side-projects/Azure-SDK-Generator-Github.png"
            class="project-img"
          />
          <h3 class="project-title">Azure SDK Convenience Wrapper Generator</h3>
          <p class="project-description">
            AI-powered tool that generates convenience wrapper methods for Azure
            SDK Java client libraries
          </p>
          <div class="tags">
            <p>Java</p>
            <p>OpenAI</p>
            <p>MCP</p>
            <p>Azure</p>
          </div>
        </a>
        <a
          class="project"
          href="https://github.com/adub20018/rapGPT"
          target="_blank"
        >
          <img
            src="../assets/side-projects/rapGPT-img.png"
            class="project-img"
          />
          <h3 class="project-title">RapGPT</h3>
          <p class="project-description">
            Premium dashboard to view user metrics for the open source project
            Unmanic
          </p>
          <div class="tags">
            <p>React</p>
            <p>Next.js</p>
            <p>OpenAI</p>
          </div>
        </a>
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
  gap: 0.5rem;
}
.project {
  text-decoration: none;
  color: var(--color-text);
  margin-top: 0.5rem;
  margin-bottom: 1.5rem;
  padding: 0.8rem;
  transition: ease-in-out 0.2s;
  border-radius: 1rem;
}
.project:hover {
  background-color: var(--color-background-transparent);
  padding: 0.8rem;
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
