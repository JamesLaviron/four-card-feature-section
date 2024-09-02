<template>
  <main>
    <header class="header">
      <div class="header__titles">
        <h1 class="header__title">Reliable, efficient delivery</h1>
        <h2 class="header__subtitle">Powered by Technology</h2>
      </div>
      <p class="header__description">
        Our Artificial Intelligence powered tools use millions of project data
        points to ensure that your project is successful
      </p>
    </header>
    <div class="content">
      <article class="content__card">
        <section>
          <h3 class="content__card-title">Supervisor</h3>
          <p class="content__card-description">
            Monitors activity to identify project roadblocks
          </p>
        </section>
        <div class="content__icon-container">
          <img
            src="./assets/images/icon-supervisor.svg"
            alt="Supervisor Icon"
            class="content__card-icon"
          />
        </div>
      </article>
      <article class="content__card">
        <section>
          <h3 class="content__card-title">Team Builder</h3>
          <p class="content__card-description">
            Scans our talent network to create the optimal team for your project
          </p>
        </section>
        <div class="content__icon-container">
          <img
            src="./assets/images/icon-team-builder.svg"
            alt="Supervisor Icon"
            class="content__card-icon"
          />
        </div>
      </article>
      <article class="content__card">
        <section>
          <h3 class="content__card-title">Karma</h3>
          <p class="content__card-description">
            Regularly evaluates our talent to ensure quality
          </p>
        </section>
        <div class="content__icon-container">
          <img
            src="./assets/images/icon-karma.svg"
            alt="Supervisor Icon"
            class="content__card-icon"
          />
        </div>
      </article>
      <article class="content__card">
        <section>
          <h3 class="content__card-title">Calculator</h3>
          <p class="content__card-description">
            Uses data from past projects to provide better delivery estimates
          </p>
        </section>
        <div class="content__icon-container">
          <img
            src="./assets/images/icon-calculator.svg"
            alt="Supervisor Icon"
            class="content__card-icon"
          />
        </div>
      </article>
    </div>
  </main>
</template>

<script>
import "./assets/styles/main.scss";
export default {
  name: "App",
  components: {},
};
</script>
