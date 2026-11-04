---
layout: default
title: Home
---

<style>
/* ========================================
   RESET PAGE WIDTH
======================================== */

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

.page-heading,
.post-header {
  display: none !important;
}

/* ========================================
   HOMEPAGE
======================================== */

.homepage {
  width: 86% !important;
  max-width: 1250px !important;
  margin: 0 auto !important;
  padding: 0 10px !important;
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

/* ========================================
   HERO
======================================== */

.homepage .hero {
  padding: 75px 0 75px;
}

.homepage .hero-layout {
  display: grid;
  grid-template-columns: minmax(0, 1fr) 290px;
  align-items: center;
  gap: 65px;
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
  font-size: clamp(38px, 5vw, 68px);
  font-weight: 700;
  letter-spacing: -0.055em;
  line-height: 1.1;
  white-space: nowrap;
  margin: 0 0 30px;
}

.homepage .hero-description {
  width: 100%;
  max-width: 800px;
  font-size: 19px;
  line-height: 1.75;
  color: #666;
  margin: 0;
}

/* ========================================
   LINKEDIN AND RESUME BUTTONS
======================================== */

.homepage .hero-links {
  display: flex;
  flex-wrap: wrap;
  gap: 16px;
  margin-top: 35px;
}

.homepage .hero-button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  background: #252525;
  color: #ffffff !important;
  border: none !important;
  border-radius: 12px;
  padding: 14px 27px;
  font-size: 16px;
  font-weight: 500;
  text-decoration: none !important;
  transition: background 0.2s ease,
              transform 0.2s ease;
}

.homepage .hero-button:hover {
  background: #444;
  transform: translateY(-2px);
}

/* ========================================
   PROFILE PHOTO
======================================== */

.homepage .hero-photo {
  width: 100%;
}

.homepage .hero-photo img {
  width: 100%;
  aspect-ratio: 4 / 5;
  object-fit: cover;
  border-radius: 14px;
  display: block;
}

/* ========================================
   SECTION HEADING
======================================== */

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

/* ========================================
   PROJECT GRID
======================================== */

.homepage .project-grid {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 24px;
  width: 100%;
}

.homepage .project-card {
  display: block;
  min-width: 0;
}

/* Images fill their containers completely */

.homepage .image-wrapper {
  width: 100%;
  aspect-ratio: 1.45 / 1;
  overflow: hidden;
  border-radius: 12px;
  background: #eeeeee;
  display: block;
  padding: 0 !important;
  margin: 0 !important;
}

.homepage .project-image {
  width: 100% !important;
  height: 100% !important;
  aspect-ratio: auto !important;
  object-fit: cover !important;
  object-position: center;
  display: block;
  margin: 0 !important;
  padding: 0 !important;
  border-radius: 0;
  box-shadow: none;
  transition: transform 0.35s ease;
}

.homepage .project-card:hover .project-image {
  transform: scale(1.045);
}

/* ========================================
   PROJECT TEXT
======================================== */

.homepage .project-info {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  gap: 10px;
  padding-top: 15px;
}

.homepage .project-info h3 {
  font-family: Georgia, serif;
  font-size: 21px;
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

/* ========================================
   FOOTER
======================================== */

.homepage .portfolio-footer {
  margin-top: 95px;
  border-top: 1px solid #ddd;
  padding: 30px 0 55px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 20px;
  flex-wrap: wrap;
  font-size: 14px;
  color: #777;
  background: transparent !important;
  box-shadow: none !important;
}

.homepage .footer-links {
  display: flex;
  gap: 28px;
}

.homepage .footer-links a {
  color: #777;
  transition: color 0.2s;
}

.homepage .footer-links a:hover {
  color: #111;
}

.site-footer,
footer.site-footer {
  background: transparent !important;
  box-shadow: none !important;
}

/* ========================================
   TABLET
======================================== */

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

/* ========================================
   MOBILE
======================================== */

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

<div class="homepage" id="top">

  <!-- =====================================
       HERO
  ===================================== -->

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

  <!-- =====================================
       SELECTED WORK
  ===================================== -->

  <section id="projects">

    <div class="section-heading">
      <h2>Selected Work</h2>
      <span>01 / Projects</span>
    </div>

    <div class="project-grid">

      <!-- 1. ISS MIMIC -->

      <a class="project-card"
         href="{{ '/projects/iss-mimic/' | relative_url }}">

        <div class="image-wrapper">

          <img class="project-image"
               src="{{ '/assets/images/iss-mimic.jpg' | relative_url }}"
               alt="ISS Mimic robotic mechanism">

        </div>

        <div class="project-info">

          <div>
            <h3>ISS Mimic</h3>
            <p>Gear Design · Mechanical Systems · Robotics</p>
          </div>

          <span class="project-year">2026</span>

        </div>

      </a>

      <!-- 2. SUBMERSIBLE XRP -->

      <a class="project-card"
         href="{{ '/projects/submersible-xrp/' | relative_url }}">

        <div class="image-wrapper">

          <img class="project-image"
               src="{{ '/assets/images/submersible_xrp.jpeg' | relative_url }}"
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

      <!-- 3. SMARTSWEEP -->

      <a class="project-card"
         href="{{ '/projects/smartsweep/' | relative_url }}">

        <div class="image-wrapper">

          <img class="project-image"
               src="{{ '/assets/images/smart_sweep.jpeg' | relative_url }}"
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

      <!-- 4. AR KART -->

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

  <!-- =====================================
       FOOTER
  ===================================== -->

  <footer class="portfolio-footer">

    <span>© 2026 Jenny Wu</span>

    <div class="footer-links">

      <a href="{{ '/projects/' | relative_url }}">
        Projects
      </a>

      <a href="#top">
        Home
      </a>

    </div>

  </footer>

</div>
