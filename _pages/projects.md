---
layout: default
title: Projects
permalink: /projects/
---

<style>
/* ===== OVERRIDE DEFAULT LAYOUT WIDTH ===== */

main,
main .wrapper,
.page-content,
.page-content .wrapper,
.container {
  max-width: none !important;
  width: 100% !important;
}

/* ===== PROJECTS PAGE ===== */

.projects-page {
  max-width: 1200px;
  width: calc(100% - 60px);
  margin: 0 auto;
  padding: 75px 0 90px;
  font-family: "Helvetica Neue", Arial, sans-serif;
  color: #222;
}

.projects-page * {
  box-sizing: border-box;
}

.projects-page a {
  color: inherit;
  text-decoration: none;
}

/* ===== INTRODUCTION ===== */

.projects-intro {
  margin-bottom: 55px;
}

.projects-label {
  font-size: 12px;
  font-weight: 700;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: #888;
  margin-bottom: 22px;
}

.projects-intro h1 {
  font-size: clamp(44px, 5vw, 68px);
  font-weight: 600;
  letter-spacing: -0.055em;
  line-height: 1.1;
  margin: 0 0 22px;
}

.projects-intro p {
  max-width: 800px;
  font-size: 18px;
  line-height: 1.7;
  color: #666;
  margin: 0;
}

/* ===== PROJECT GRID ===== */

.projects-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  column-gap: 30px;
  row-gap: 65px;
}

.project-card {
  display: block;
  min-width: 0;
}

/* ===== IMAGES ===== */

.project-image-wrap {
  width: 100%;
  aspect-ratio: 4 / 3;
  overflow: hidden;
  border-radius: 12px;
  background: #f0f0f0;
}

.project-image-wrap img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
  transition: transform 0.4s ease;
}

.project-card:hover img {
  transform: scale(1.035);
}

/* ===== PROJECT TITLES ===== */

.project-heading {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  gap: 12px;
  margin-top: 17px;
}

.project-heading h2 {
  font-family: Georgia, "Times New Roman", serif;
  font-size: 27px;
  font-weight: 700;
  letter-spacing: -0.8px;
  line-height: 1.2;
  margin: 0;
}

.project-year {
  font-size: 14px;
  color: #999;
  white-space: nowrap;
}

.project-description {
  font-size: 15px;
  color: #777;
  line-height: 1.6;
  margin-top: 10px;
}

/* ===== FOOTER ===== */

.projects-footer {
  margin-top: 90px;
  padding-top: 28px;
  border-top: 1px solid #ddd;
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 20px;
  font-size: 14px;
  color: #888;
}

.projects-footer a:hover {
  color: #222;
}

/* ===== MOBILE ===== */

@media (max-width: 700px) {
  .projects-page {
    width: calc(100% - 36px);
    padding: 50px 0 70px;
  }

  .projects-grid {
    grid-template-columns: 1fr;
    row-gap: 45px;
  }

  .projects-intro {
    margin-bottom: 40px;
  }

  .projects-intro p {
    font-size: 16px;
  }

  .project-heading h2 {
    font-size: 25px;
  }
}
</style>

<div class="projects-page" id="top">

  <!-- INTRODUCTION -->

  <section class="projects-intro">


    <h1>Click project photos below to learn more!</h1>

    <p>
      Each project highlights the engineering decisions,
      technical challenges, and lessons learned throughout
      the design process.
    </p>

  </section>

  <!-- ALL SIX PROJECTS -->

  <div class="projects-grid">

    <!-- 1. ISS MIMIC -->

    <a class="project-card"
       href="{{ '/projects/iss-mimic/' | relative_url }}">

      <div class="project-image-wrap">
        <img
          src="{{ '/assets/images/iss-mimic.jpg' | relative_url }}"
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
        <span class="project-year">2026</span>
      </div>

      <p class="project-description">
        Steering Geometry · CAD · 3D Printing
      </p>
    </a>

    <!-- 5. FLUID MECHANICS -->

    <a class="project-card"
       href="{{ '/projects/fluid-mechanical-dissection/' | relative_url }}">

      <div class="project-image-wrap">
        <img
          src="{{ '/assets/images/lifting-device-design.png' | relative_url }}"
          alt="Fluid Mechanics">
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
          src="{{ '/assets/images/heat-exchanger.jpg' | relative_url }}"
          alt="Heat Exchanger">
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
