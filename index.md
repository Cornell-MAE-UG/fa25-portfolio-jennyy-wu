---
layout: default
title: Home
---

<style>

/* ===== FULL WIDTH LAYOUT ===== */

.page-content .wrapper,
.page-content .container,
main .wrapper {
  max-width: 1500px !important;
  width: 96% !important;
}

.homepage {
  width: 100%;
  max-width: 1400px;
  margin: 0 auto;
  padding: 0 38px;
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

/* ===== HERO SECTION ===== */

.homepage .hero {
  padding: 85px 0 75px;
}

.homepage .hero-layout {
  display: grid;
  grid-template-columns: minmax(0, 1fr) 300px;
  align-items: center;
  gap: 75px;
}

.homepage .hero-content {
  min-width: 0;
}

.homepage .eyebrow {
  font-family: "Helvetica Neue", Arial, sans-serif;
  font-size: 13px;
  font-weight: 700;
  letter-spacing: 2.3px;
  text-transform: uppercase;
  color: #777;
  margin-bottom: 32px;
}

.homepage .hero h1 {
  font-family: "Helvetica Neue", Arial, sans-serif;
  font-size: clamp(42px, 5vw, 72px);
  font-weight: 700;
  letter-spacing: -0.055em;
  line-height: 1.1;
  white-space: nowrap;
  margin: 0 0 32px;
}

.homepage .hero-description {
  max-width: 850px;
  font-size: 20px;
  line-height: 1.75;
  color: #666;
  margin: 0;
}

.homepage .hero-links {
  display: flex;
  gap: 40px;
  margin-top: 35px;
  flex-wrap: wrap;
}

.homepage .hero-links a {
  display: inline-block;
  font-size: 16px;
  font-weight: 600;
  padding-bottom: 6px;
  border-bottom: 1px solid #222;
  transition: opacity 0.2s ease;
}

.homepage .hero-links a:hover {
  opacity: 0.55;
}

/* ===== PROFILE PHOTO ===== */

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

/* ===== SECTION HEADING ===== */

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

/* ===== FOUR PROJECTS IN ONE ROW ===== */

.homepage .project-grid {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 28px;
}

.homepage .project-card {
  display: block;
  min-width: 0;
}

.homepage .image-wrapper {
  width: 100%;
  overflow: hidden;
  border-radius: 10px;
  background: #eeeeee;
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

/* ===== FOOTER ===== */

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
}

.homepage .footer-links {
  display: flex;
  gap: 25px;
}

.homepage .footer-links a:hover {
  color: #111;
}

/* ===== TABLET ===== */

@media (max-width: 1050px) {

  .homepage .hero-layout {
    grid-template-columns: minmax(0, 1fr) 250px;
    gap: 35px;
  }

  .homepage .hero h1 {
    font-size: clamp(36px, 5vw, 55px);
  }

  .homepage .project-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 40px 24px;
  }

}

/* ===== MOBILE ===== */

@media (max-width: 650px) {

  .homepage {
    padding: 0 15px;
  }

  .homepage .hero {
    padding: 45px 0 60px;
  }

  .homepage .hero-layout {
    grid-template-columns: 1fr;
    gap: 35px;
  }

  .homepage .hero h1 {
    font-size: clamp(34px, 9vw, 48px);
    white-space: normal;
    margin-bottom: 22px;
  }

  .homepage .eyebrow {
    font-size: 11px;
    letter-spacing: 1.4px;
    margin-bottom: 22px;
  }

  .homepage .hero-description {
    font-size: 17px;
    line-height: 1.7;
  }

  .homepage .hero-links {
    gap: 22px;
  }

  .homepage .hero-photo img {
    width: 100%;
    max-width: 320px;
    aspect-ratio: 4 / 5;
  }

  .homepage .project-grid {
    grid-template-columns: 1fr;
    gap: 38px;
  }

  .homepage .project-info h3 {
    font-size: 23px;
  }

  .homepage .portfolio-footer {
    margin-top: 65px;
  }

}

</style>

<div class="homepage">

  <!-- ===== INTRODUCTION ===== -->

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

          <a href="#projects">
            Explore my work ↗
          </a>

          <a href="#about">
            More about me ↗
          </a>

        </div>

      </div>

      <!-- PROFILE PICTURE -->

      <div class="hero-photo">

        <img
          src="{{ '/assets/images/profile.jpg' | relative_url }}"
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


      <!-- ===== 1. ISS MIMIC ===== -->

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
            <p>
              Gear Design · Mechanical Systems · Robotics
            </p>
          </div>

          <span class="project-year">2026</span>

        </div>

      </a>


      <!-- ===== 2. SUBMERSIBLE XRP ===== -->

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
            <p>
              Underwater Robotics · CAD · Prototyping
            </p>
          </div>

          <span class="project-year">2026</span>

        </div>

      </a>


      <!-- ===== 3. SMARTSWEEP ===== -->

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
            <p>
              Product Development · Mechanical Design
            </p>
          </div>

          <span class="project-year">2026</span>

        </div>

      </a>


      <!-- ===== 4. AR KART ===== -->

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
            <p>
              Steering Geometry · CAD · 3D Printing
            </p>
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

      <a href="https://www.linkedin.com/"
         target="_blank"
         rel="noopener noreferrer">
        LinkedIn
      </a>

      <a href="{{ '/assets/Jenny_Wu_Resume.pdf' | relative_url }}"
         target="_blank">
        Resume
      </a>

      <a href="mailto:YOUR_EMAIL@example.com">
        Email
      </a>

    </div>

  </footer>

</div>
