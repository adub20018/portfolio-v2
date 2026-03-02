<template>
  <div class="card profile-card">
    <div class="profile">
      <img src="../assets/profile-pic.png" class="profile-pic" />
      <div class="profile-section">
        <h1>Alex Malone</h1>
        <p class="job">Software Developer</p>
        <!-- <div class="profile-section">
          <p class="job">Software Developer</p>
        </div> -->
      </div>
    </div>

    <div class="divider"></div>

    <div class="contact">
      <a class="contact-link" href="mailto:alex.w.malone128@gmail.com">
        <div class="icon-container">
          <img src="../assets/mail-logo.svg" />
        </div>
        <div class="contact-content">
          <p class="text-passive">EMAIL</p>
          <p>alex.w.malone128@gmail.com</p>
        </div>
      </a>
      <a class="contact-link" href="tel:alex.w.malone128@gmail.com">
        <div class="icon-container">
          <img src="../assets/phone.svg" />
        </div>
        <div class="contact-content">
          <p class="text-passive">PHONE</p>
          <p>+64 27 382 7597</p>
        </div>
      </a>
      <a
        class="contact-link"
        href="https://www.google.com/maps/place/melbourne/data=!4m2!3m1!1s0x6ad646b5d2ba4df7:0x4045675218ccd90?sa=X&ved=1t:155783&ictx=111"
        target="_blank"
      >
        <div class="icon-container">
          <img src="../assets/map-pin.svg" />
        </div>
        <div class="contact-content">
          <p class="text-passive">LOCATION</p>
          <p>Melbourne, Australia</p>
        </div>
      </a>
    </div>

    <div class="divider"></div>

    <!-- <div class="nav">
      <a>About Me</a>
      <a>Projects</a>
    </div> -->

    <div class="social-links">
      <div>
        <a
          href="https://www.linkedin.com/in/alex-malone-6487ba231/"
          target="_blank"
        >
          <svg
            class="social-icon"
            viewBox="0 0 72 72"
            height="32"
            width="32"
            aria-hidden="true"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              fill="#ffffffa6"
              d="M8,72 L64,72 C68.418278,72 72,68.418278 72,64 L72,8 C72,3.581722 68.418278,-8.11624501e-16 64,0 L8,0 C3.581722,8.11624501e-16 -5.41083001e-16,3.581722 0,8 L0,64 C5.41083001e-16,68.418278 3.581722,72 8,72 Z"
            />
            <path
              d="M62,62 L51.315625,62 L51.315625,43.8021149 C51.315625,38.8127542 49.4197917,36.0245323 45.4707031,36.0245323 C41.1746094,36.0245323 38.9300781,38.9261103 38.9300781,43.8021149 L38.9300781,62 L28.6333333,62 L28.6333333,27.3333333 L38.9300781,27.3333333 L38.9300781,32.0029283 C38.9300781,32.0029283 42.0260417,26.2742151 49.3825521,26.2742151 C56.7356771,26.2742151 62,30.7644705 62,40.051212 L62,62 Z M16.349349,22.7940133 C12.8420573,22.7940133 10,19.9296567 10,16.3970067 C10,12.8643566 12.8420573,10 16.349349,10 C19.8566406,10 22.6970052,12.8643566 22.6970052,16.3970067 C22.6970052,19.9296567 19.8566406,22.7940133 16.349349,22.7940133 Z M11.0325521,62 L21.769401,62 L21.769401,27.3333333 L11.0325521,27.3333333 L11.0325521,62 Z"
            />
          </svg>
        </a>
        <a href="https://github.com/adub20018" target="_blank">
          <svg
            class="social-icon"
            viewBox="0 0 16 16"
            aria-hidden="true"
            width="32"
            height="32"
          >
            <path
              fill="#ffffffa6"
              d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.012 8.012 0 0 0 16 8c0-4.42-3.58-8-8-8z"
            ></path>
          </svg>
        </a>
      </div>
    </div>
  </div>
</template>

<style scoped>
.profile-card {
  display: flex;
  flex-direction: column;
  position: sticky;
  top: 2rem;
  max-height: calc(100vh - 4rem);
}
.profile {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.profile-pic {
  max-width: 128px;
  background-color: var(--color-background-transparent);
  border-radius: 12px;
}
.profile-pic img {
  max-width: 128px;
}

.profile-section {
  margin-top: 1rem;
}

.name {
  font-size: 36px;
}
.job {
  margin-top: 0.5rem;
  background-color: var(--color-background-transparent);
  text-align: center;
  border-radius: 12px;
}

.nav {
  padding: 1rem 0;
  display: flex;
  flex-direction: column;
}

.contact {
  display: flex;
  flex-direction: column;
  gap: 0.5rem;
}
.contact-link {
  display: flex;
  gap: 0.5rem;
  line-height: 1.2;
  color: var(--color-text);
  text-decoration: none;
  border-radius: 0.5rem;
  padding: 0.5rem;
}
.contact-link:hover {
  background-color: var(--color-background-transparent);
}
.contact-link {
}
.icon-container {
  /* background-color: var(--color-background-transparent); */
  width: fit-content;
  padding: 0.5rem;
  height: 40px;
  width: 40px;
  border-radius: 6px;
}

.social-links {
  margin-top: auto;
}
.social-links > div {
  display: flex;
  justify-content: flex-start;
  gap: 0.5rem;
}

@media screen and (max-width: 972px) {
  .profile-card {
    position: static;
    align-items: center;
    max-height: 100%;
  }
  .social-links > div {
    justify-content: center;
  }
}
</style>
