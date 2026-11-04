---
layout: default
title: Projects
permalink: /projects/
---

<style>
/* FULL-WIDTH PAGE OVERRIDE */
main, .page-content, .wrapper, .container {
  max-width: none !important;
}

.projects-page {
  max-width: 1180px;
  width: calc(100% - 60px);
  margin: 0 auto;
  padding: 85px 0 100px;
  color: #222;
  font-family: "Helvetica Neue", Arial, sans-serif;
}

.projects-page * {
  box-sizing: border-box;
}

.projects-page a {
  color: inherit;
  text-decoration: none;
}

/* INTRO */
.projects-intro {
  margin-bottom: 65px;
}

.projects-label {
  font-size: 12px;
  font-weight: 700;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: #888;
  margin-bottom: 24px;
}

.projects-intro h1 {
  font-size: clamp(46px, 6vw, 78px);
  font-weight: 600;
  letter-spacing: -0.055em;
  line-height: 1.05;
  margin: 0 0 24px;
}

.projects-intro p {
  max-width: 650px;
  font-size: 19px;
  line-height: 1.7;
  color: #666;
  margin: 0;
}

/* GRID */
.projects-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  column-gap: 35px;
  row-gap: 75px;
}

.project-card {
  display: block;
  min-width: 0;
}

/* LARGE PHOTOS */
.project-image-wrap {
  width: 100%;
  aspect-ratio: 4 / 3;
  overflow: hidden;
  border-radius: 12px;
  background: #eeeeee;
}

.project-image-wrap img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
  transition: transform 0.4s ease;
}

.project-card:hover img {
  transform: scale(1.04);
}

/* PROJECT TEXT */
.project-heading {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  gap: 15px;
  margin-top: 20px;
}

.project-heading h2 {
  font-family: Georgia, "Times New Roman", serif;
  font-size: clamp(24px, 2.5vw, 32px);
  font-weight: 700;
  letter-spacing: -1px;
  line-height: 1.2;
  margin: 0;
}

.project-year {
  color: #999;
  font-size: 15px;
  white-space: nowrap;
}

.project-description {
  font-size: 16px;
  color: #777;
  line-height: 1.6;
  margin-top: 12px;
}

/* FOOTER */
.projects-footer {
  margin-top: 100px;
  padding-top: 30px;
  border-top: 1px solid #ddd;
  display: flex;
  justify-content: space-between;
  gap: 20px;
  font-size: 14px;
  color: #888;
}

.projects-footer a:hover {
  color: #222;
}

/* MOBILE */
@media (max-width: 700px) {
  .projects-page {
    width: calc(100% - 36px);
    padding: 55px 0 70px;
  }

  .projects-grid {
    grid-template-columns: 1fr;
    row-gap: 48px;
  }

  .projects-intro {
    margin-bottom: 45px;
  }

  .projects-intro p {
    font-size: 17px;
  }

  .project-heading h2 {
    font-size: 26px;
  }
}
</style>

<div class="projects-page" id="top">

  <!-- INTRODUCTION -->

  <section class="projects-intro">
    <div class="projects-label">
      MECHANICAL ENGINEERING · SELECTED PROJECTS
    </div>

    <h1>Things I've built.</h1>

    <p>
      A collection of projects I've worked on,
      from robotics and mechanical mechanisms
      to hands-on design and prototyping.
      Click on a project to see the design process,
      challenges, and engineering behind it.
    </p>
  </section>

  <!-- SIX PROJECTS -->

  <div class="projects-grid">

    <!-- 1. ISS MIMIC -->
    <a class="project-card"
       href="{{ '/projects/iss-mimic/' | relative_url }}">

      <div class="project-image-wrap">
        <img
          src="{{ '/assets/images/iss-mimic.jpeg' | relative_url }}"
          alt="ISS Mimic">
      </div>

      <div class="project-heading">
        <h2>ISS Mimic</h2>
        <span class="project-year">2026</span>
      </div>

      <p class="project-description">
        Gear Design · Mechanical Systems · Robotics
      </p>
    </a>

    <!-- 2. SUBMERSIBLE XRP -->
    <a class="project-card"
       href="{{ '/projects/submersible-xrp/' | relative_url }}">

      <div class="project-image-wrap">
        <img
          src="{{ '/assets/images/submersible.jpeg' | relative_url }}"
          alt="Submersible XRP">
      </div>

      <div class="project-heading">
        <h2>Submersible XRP</h2>
        <span class="project-year">2026</span>
      </div>

      <p class="project-description">
        Underwater Robotics · CAD · Prototyping
      </p>
    </a>

    <!-- 3. SMARTSWEEP -->
    <a class="project-card"
       href="{{ '/projects/smart-sweep/' | relative_url }}">

      <div class="project-image-wrap">
        <img
          src="{{ '/assets/images/smartsweep.jpeg' | relative_url }}"
          alt="SmartSweep">
      </div>

      <div class="project-heading">
        <h2>SmartSweep</h2>
        <span class="project-year">2026</span>
      </div>

      <p class="project-description">
        Product Development · Mechanical Design
      </p>
    </a>

    <!-- 4. AR KART -->
    <a class="project-card"
       href="{{ '/projects/ar-kart/' | relative_url }}">

      <div class="project-image-wrap">
        <img
          src="{{ '/assets/images/ar-kart.png' | relative_url }}"
          alt="AR Kart">
      </div>

      <div class="project-heading">
        <h2>AR Kart</h2>
        <span class="project-year">2025</span>
      </div>

      <p class="project-description">
        Steering Geometry · CAD · 3D Printing
      </p>
    </a>

    <!-- 5. FLUID MECHANICS -->
    <a class="project-card"
       href="{{ '/projects/fluid-mechanical/' | relative_url }}">

      <div class="project-image-wrap">
        <img
          src="{{ '/assets/images/fluid-mechanics.jpeg' | relative_url }}"
          alt="Fluid Mechanics project">
      </div>

      <div class="project-heading">
        <h2>Fluid Mechanics</h2>
        <span class="project-year">2026</span>
      </div>

      <p class="project-description">
        Fluid Systems · Engineering Analysis
      </p>
    </a>

    <!-- 6. HEAT EXCHANGER -->
    <a class="project-card"
       href="{{ '/projects/heat-exchanger/' | relative_url }}">

      <div class="project-image-wrap">
        <img
          src="{{ '/assets/images/heat-exchanger.jpeg' | relative_url }}"
          alt="Heat Exchanger project">
      </div>

      <div class="project-heading">
        <h2>Heat Exchanger</h2>
        <span class="project-year">2025</span>
      </div>

      <p class="project-description">
        Thermal Systems · Heat Transfer · Design
      </p>
    </a>

  </div>

  <!-- FOOTER -->
  <footer class="projects-footer">
    <span>© 2026 Jenny Wu</span>
    <a href="#top">Back to top ↑</a>
  </footer>

</div>
