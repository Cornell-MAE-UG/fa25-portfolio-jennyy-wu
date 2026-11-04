
---
layout: default
title: Home
---

<style>

/* ===== REMOVE THEME WIDTH RESTRICTIONS ===== */

html, body {
  width: 100%;
  max-width: none !important;
}

.page-content,
.page-content > .wrapper,
.page-content > .container,
main,
main > .wrapper,
main > .container {
  width: 100% !important;
  max-width: none !important;
  box-sizing: border-box;
}

/* ===== HOMEPAGE ===== */

.homepage {
  width: min(96vw, 1600px) !important;
  max-width: none !important;
  margin: 0 auto !important;
  padding: 0 35px !important;
  box-sizing: border-box;
  font-family: "Helvetica Neue", Arial, sans-serif;
  color: #202020;
}

.homepage * {
  box-sizing: border-box;
}

.homepage a {
  color: inherit;
  text-decoration: none;
}

/* ===== HERO ===== */

.homepage .hero {
  padding: 85px 0 75px;
}

.homepage .hero-layout {
  display: grid;
  grid-template-columns: minmax(0, 1fr) 300px;
  align-items: center;
  gap: 70px;
  width: 100%;
}

.homepage .hero-content {
  min-width: 0;
}

.homepage .eyebrow {
  font-size: 13px;
  font-weight: 700;
  letter-spacing: 2.2px;
  text-transform: uppercase;
  color: #777;
  margin-bottom: 32px;
}

.homepage .hero h1 {
  font-family: "Helvetica Neue", Arial, sans-serif;
  font-size: clamp(38px, 5vw, 70px);
  font-weight: 700;
  letter-spacing: -0.055em;
  line-height: 1.1;
  white-space: nowrap;
  margin: 0 0 30px;
}

.homepage .hero-description {
  width: 100%;
  max-width: 850px;
  font-size: 20px;
  line-height: 1.75;
  color: #666;
  margin: 0;
}

/* ===== BLACK BUTTONS ===== */

.homepage .hero-links {
  display: flex;
  flex-wrap: wrap;
  gap: 16px;
  margin-top: 35px;
}

.homepage .hero-links .hero-button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  background: #252525;
  color: #fff !important;
  border: none !important;
  border-radius: 12px;
  padding: 14px 27px;
  font-size: 16px;
  font-weight: 500;
  text-decoration: none !important;
  transition: background 0.2s ease, transform 0.2s ease;
}

.homepage .hero-links .hero-button:hover {
  background: #444;
  transform: translateY(-2px);
}

/* ===== PROFILE PHOTO ===== */

.homepage .hero-photo img {
  width: 100%;
  aspect-ratio: 4 / 5;
  object-fit: cover;
  border-radius: 14px;
  display: block;
}

/* ===== SECTION HEADINGS ===== */

.homepage .section-heading {
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-top: 1px solid #d8d8d8;
  padding: 24px 0;
  margin-bottom: 18px;
}

.homepage .section-heading h2 {
  font-family: Georgia, serif;
  font-size: 23px;
  font-weight: 700;
  margin: 0;
}

.homepage .section-heading span {
  font-size: 14px;
  color: #888;
}

/* ===== PROJECT GRID ===== */

.homepage .project-grid {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 28px;
  width: 100%;
}

.homepage .project-card {
  display: block;
  min-width: 0;
}

.homepage .image-wrapper {
  width: 100%;
  overflow: hidden;
  border-radius: 10px;
  background: #eee;
}

.homepage .project-image {
  width: 100%;
  aspect-ratio: 1.65 / 1;
  object-fit: cover;
  display: block;
  transition: transform 0.35s ease;
}

.homepage .project-card:hover .project-image {
  transform: scale(1.045);
}

.homepage .project-info {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  gap: 10px;
  padding-top: 15px;
}

.homepage .project-info h3 {
  font-family: Georgia, serif;
  font-size: 22px;
  font-weight: 700;
  line-height: 1.2;
  margin: 0 0 10px;
  letter-spacing: -0.4px;
}

.homepage .project-info p {
  font-size: 14px;
  color: #777;
  line-height: 1.55;
  margin: 0;
}

.homepage .project-year {
  font-size: 13px;
  color: #999;
  white-space: nowrap;
  padding-top: 4px;
}

/* ===== CLEAN FOOTER ===== */

.homepage .portfolio-footer {
  margin-top: 100px;
  border-top: 1px solid #ddd;
  padding: 30px 0 55px;
  display: flex;
  justify-content: space-between;
  gap: 20px;
  flex-wrap: wrap;
  font-size: 14px;
  color: #777;
  background: transparent !important;
  box-shadow: none !important;
}

.homepage .footer-links {
  display: flex;
  gap: 25px;
}

.homepage .footer-links a:hover {
  color: #111;
}

.site-footer,
footer.site-footer {
  background: transparent !important;
  box-shadow: none !important;
}

/* ===== TABLET ===== */

@media (max-width: 1050px) {

  .homepage .hero-layout {
    grid-template-columns: minmax(0, 1fr) 240px;
    gap: 30px;
  }

  .homepage .hero h1 {
    font-size: clamp(36px, 5vw, 55px);
  }

  .homepage .project-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}

/* ===== MOBILE ===== */

@media (max-width: 650px) {

  .homepage {
    width: 100% !important;
    padding: 0 20px !important;
  }

  .homepage .hero {
    padding: 45px 0 60px;
  }

  .homepage .hero-layout {
    grid-template-columns: 1fr;
    gap: 35px;
  }

  .homepage .hero h1 {
    font-size: 38px;
    white-space: normal;
  }

  .homepage .hero-description {
    font-size: 17px;
  }

  .homepage .eyebrow {
    font-size: 11px;
    letter-spacing: 1.4px;
  }

  .homepage .hero-photo img {
    max-width: 320px;
  }

  .homepage .project-grid {
    grid-template-columns: 1fr;
    gap: 38px;
  }

  .homepage .portfolio-footer {
    margin-top: 65px;
  }
}

</style>

<div class="homepage">

  <!-- ===== HERO ===== -->

  <section class="hero">

    <div class="hero-layout">

      <div class="hero-content">

        <div class="eyebrow">
          MECHANICAL ENGINEERING · CORNELL UNIVERSITY
        </div>

        <h1>Hi, I'm Jenny.</h1>

        <p class="hero-description">
          I'm a mechanical engineering student at Cornell
          University with a passion for robotics, product
          design, and hands-on problem solving.
          I love turning ideas into real, working things.
        </p>

        <div class="hero-links">

          <a
            href="https://www.linkedin.com/in/"
            class="hero-button"
            target="_blank"
            rel="noopener noreferrer">
            LinkedIn
          </a>

          <a
            href="{{ '/assets/Jenny_Wu_Resume.pdf' | relative_url }}"
            class="hero-button"
            target="_blank"
            rel="noopener noreferrer">
            Resume
          </a>

        </div>

      </div>

      <!-- PROFILE PHOTO -->

      <div class="hero-photo">

        <img
          src="{{ '/assets/images/profile.png' | relative_url }}"
          alt="Jenny Wu"
        >

      </div>

    </div>

  </section>

  <!-- ===== SELECTED WORK ===== -->

  <section id="projects">

    <div class="section-heading">
      <h2>Selected Work</h2>
      <span>01 / Projects</span>
    </div>

    <div class="project-grid">

      <!-- ISS MIMIC -->

      <a class="project-card"
         href="{{ '/projects/iss-mimic/' | relative_url }}">

        <div class="image-wrapper">
          <img class="project-image"
               src="{{ '/assets/images/iss-mimic.jpg' | relative_url }}"
               alt="ISS Mimic robotics project">
        </div>

        <div class="project-info">
          <div>
            <h3>ISS Mimic</h3>
            <p>Gear Design · Mechanical Systems · Robotics</p>
          </div>
          <span class="project-year">2026</span>
        </div>

      </a>

      <!-- SUBMERSIBLE XRP -->

      <a class="project-card"
         href="{{ '/projects/submersible-xrp/' | relative_url }}">

        <div class="image-wrapper">
          <img class="project-image"
               src="{{ '/assets/images/submersible-xrp.jpeg' | relative_url }}"
               alt="Submersible XRP underwater robot">
        </div>

        <div class="project-info">
          <div>
            <h3>Submersible XRP</h3>
            <p>Underwater Robotics · CAD · Prototyping</p>
          </div>
          <span class="project-year">2026</span>
        </div>

      </a>

      <!-- SMARTSWEEP -->

      <a class="project-card"
         href="{{ '/projects/smartsweep/' | relative_url }}">

        <div class="image-wrapper">
          <img class="project-image"
               src="{{ '/assets/images/smartsweep.jpg' | relative_url }}"
               alt="SmartSweep mechanical prototype">
        </div>

        <div class="project-info">
          <div>
            <h3>SmartSweep</h3>
            <p>Product Development · Mechanical Design</p>
          </div>
          <span class="project-year">2026</span>
        </div>

      </a>

      <!-- AR KART -->

      <a class="project-card"
         href="{{ '/projects/ar-kart/' | relative_url }}">

        <div class="image-wrapper">
          <img class="project-image"
               src="{{ '/assets/images/ar-kart.png' | relative_url }}"
               alt="AR Kart robotic vehicle">
        </div>

        <div class="project-info">
          <div>
            <h3>AR Kart</h3>
            <p>Steering Geometry · CAD · 3D Printing</p>
          </div>
          <span class="project-year">2025</span>
        </div>

      </a>

    </div>

  </section>

  <!-- ===== FOOTER ===== -->

  <footer class="portfolio-footer">

    <span>© 2026 Jenny Wu</span>

    <div class="footer-links">

      <a href="#projects">Projects</a>

      <a href="{{ '/about/' | relative_url }}">About</a>

    </div>

  </footer>

</div>
