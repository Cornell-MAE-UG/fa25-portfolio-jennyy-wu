---
layout: default
title: Home
---

<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">

<style>
/* ===== REMOVE THE THEME'S NARROW WIDTH ===== */

main,
main .wrapper,
.page-content,
.page-content > .wrapper,
.container {
  width: 100% !important;
  max-width: none !important;
  box-sizing: border-box !important;
}

.page-content {
  padding-top: 0 !important;
}

.page-content > .wrapper {
  padding-left: 0 !important;
  padding-right: 0 !important;
}

/* ===== HOMEPAGE ===== */

.homepage {
  width: 85%;
  max-width: 900px;
  margin: 0 auto;
  padding: 0;
  box-sizing: border-box;
  font-family: "Inter", Arial, sans-serif;
  color: #222;
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
  padding: 105px 0 90px;
}

.homepage .hero-layout {
  display: grid;
  grid-template-columns: minmax(0, 1.8fr) minmax(0, 0.75fr);
  align-items: center;
  gap: 65px;
}

.homepage .hero-content {
  min-width: 0;
}

.homepage .hero h1 {
  font-family: "DM Sans", Arial, sans-serif;
  font-size: clamp(40px, 4.5vw, 68px);
  font-weight: 700;
  letter-spacing: -0.05em;
  line-height: 1.1;
  white-space: nowrap;
  margin: 0 0 35px;
}

.homepage .hero-description {
  max-width: 750px;
  font-family: "Inter", Arial, sans-serif;
  font-size: 18px;
  font-weight: 400;
  line-height: 1.8;
  color: #666;
  margin: 0;
}

/* ===== SMALLER LINKEDIN & RESUME BUTTONS ===== */

.homepage .hero-buttons {
  display: flex;
  gap: 12px;
  flex-wrap: wrap;
  margin-top: 32px;
}

.homepage .hero-button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-width: 105px;
  padding: 12px 20px;
  border-radius: 10px;
  background: #252525;
  color: #fff !important;
  font-family: "Inter", Arial, sans-serif;
  font-size: 14px;
  font-weight: 600;
  line-height: 1.3;
  text-align: center;
  transition: background 0.2s ease, transform 0.2s ease;
}

.homepage .hero-button:hover {
  background: #444;
  transform: translateY(-2px);
}

/* ===== PROFILE PHOTO ===== */

.homepage .hero-photo {
  width: 100%;
}

.homepage .hero-photo img {
  display: block;
  width: 100%;
  height: auto;
  aspect-ratio: 4 / 5;
  object-fit: cover;
  object-position: center;
  border-radius: 14px;
  margin: 0;
  padding: 0;
  box-shadow: none;
}

/* ===== SELECTED WORK HEADING ===== */

.homepage .section-heading {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 20px;
  border-top: 1px solid #ddd;
  padding: 25px 0 35px;
}

.homepage .section-heading h2 {
  font-family: "DM Sans", Arial, sans-serif;
  font-size: 27px;
  font-weight: 700;
  letter-spacing: -0.035em;
  margin: 0;
}

.homepage .section-heading span {
  color: #888;
  font-family: "Inter", Arial, sans-serif;
  font-size: 13px;
}

/* ===== PROJECT GRID ===== */

.homepage .project-grid {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 24px;
  width: 100%;
}

.homepage .project-card {
  display: block;
  min-width: 0;
  cursor: pointer;
}

/* ===== PROJECT IMAGES ===== */

.homepage .image-wrapper {
  display: block;
  width: 100%;
  aspect-ratio: 4 / 3;
  overflow: hidden;
  border-radius: 12px;
  background: #eee;
  padding: 0 !important;
  margin: 0 !important;
}

.homepage .image-wrapper img.project-image {
  display: block !important;
  width: 100% !important;
  height: 100% !important;
  max-width: none !important;
  max-height: none !important;
  object-fit: cover !important;
  object-position: center !important;
  aspect-ratio: auto !important;
  padding: 0 !important;
  margin: 0 !important;
  border: 0 !important;
  border-radius: 0 !important;
  box-shadow: none !important;
  transition: transform 0.35s ease;
}

.homepage .project-card:hover .project-image {
  transform: scale(1.04);
}

/* ===== INDIVIDUAL PHOTO FRAMING ===== */

.homepage .project-card:nth-child(1) img {
  object-position: center 45% !important;
}

.homepage .project-card:nth-child(2) img {
  object-position: center center !important;
}

.homepage .project-card:nth-child(3) img {
  object-position: center 35% !important;
}

.homepage .project-card:nth-child(4) img {
  object-position: center center !important;
}

/* ===== PROJECT TEXT ===== */

.homepage .project-info {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  gap: 12px;
  padding-top: 17px;
}

.homepage .project-info h3 {
  font-family: "DM Sans", Arial, sans-serif;
  font-size: 23px;
  font-weight: 700;
  letter-spacing: -0.035em;
  line-height: 1.2;
  margin: 0 0 12px;
}

.homepage .project-info p {
  font-family: "Inter", Arial, sans-serif;
  font-size: 14px;
  line-height: 1.6;
  color: #777;
  margin: 0;
}

.homepage .project-year {
  font-family: "Inter", Arial, sans-serif;
  font-size: 13px;
  color: #999;
  white-space: nowrap;
  padding-top: 5px;
}

/* ===== FOOTER ===== */

.homepage .portfolio-footer {
  margin-top: 100px;
  padding: 35px 0 60px;
  border-top: 1px solid #ddd;
  background: transparent !important;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 20px;
  flex-wrap: wrap;
  font-family: "Inter", Arial, sans-serif;
  font-size: 14px;
  color: #777;
}

.homepage .footer-links {
  display: flex;
  align-items: center;
  gap: 35px;
}

.homepage .footer-links a:hover {
  color: #222;
}

/* ===== TABLET ===== */

@media (max-width: 1000px) {
  .homepage .hero-layout {
    grid-template-columns: minmax(0, 1.5fr) minmax(0, 1fr);
    gap: 35px;
  }

  .homepage .hero h1 {
    font-size: clamp(34px, 5vw, 52px);
  }

  .homepage .project-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 45px 22px;
  }
}

/* ===== MOBILE ===== */

@media (max-width: 650px) {
  .homepage {
    width: 90%;
  }

  .homepage .hero {
    padding: 55px 0 65px;
  }

  .homepage .hero-layout {
    grid-template-columns: 1fr;
    gap: 35px;
  }

  .homepage .hero h1 {
    font-size: clamp(34px, 9vw, 46px);
    white-space: normal;
  }

  .homepage .hero-description {
    font-size: 16px;
  }

  .homepage .hero-photo img {
    max-width: 360px;
  }

  .homepage .hero-button {
    min-width: 100px;
    font-size: 14px;
    padding: 12px 18px;
  }

  .homepage .project-grid {
    grid-template-columns: 1fr;
    gap: 40px;
  }

  .homepage .project-info h3 {
    font-size: 22px;
  }

  .homepage .portfolio-footer {
    margin-top: 70px;
  }

  .homepage .footer-links {
    gap: 22px;
  }
}
</style>

<div class="homepage" id="home">

  <!-- ===== ABOUT / HERO ===== -->

  <section class="hero" id="about">

    <div class="hero-layout">

      <div class="hero-content">

        <h1>Hi, I'm Jenny.</h1>

        <p class="hero-description">
          I'm a mechanical engineering student at Cornell
          University with a passion for robotics, product
          design, and hands-on problem solving. I love
          turning ideas into real, working things.
        </p>

        <div class="hero-buttons">

          <a
            href="https://www.linkedin.com/in/jenny-wu-44b5912a8/"
            class="hero-button"
            target="_blank"
            rel="noopener noreferrer">
            LinkedIn
          </a>

          <a
            href="{{ '/assets/images/Resume.pdf' | relative_url }}"
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
          alt="Jenny Wu">

      </div>

    </div>

  </section>

  <!-- ===== SELECTED WORK ===== -->

  <section id="projects">

    <div class="section-heading">
      <h2>Selected Work</h2>
      <span>Projects</span>
    </div>

    <div class="project-grid">

      <!-- 1. ISS MIMIC -->

      <a class="project-card"
         href="{{ '/projects/iss-mimic/' | relative_url }}">

        <div class="image-wrapper">
          <img
            class="project-image"
            src="{{ '/assets/images/iss-mimic.jpg' | relative_url }}"
            alt="ISS Mimic robotics project">
        </div>

        <div class="project-info">
          <div>
            <h3>ISS Mimic</h3>
          </div>
          <span class="project-year">2026</span>
        </div>

      </a>

      <!-- 2. SUBMERSIBLE XRP -->

      <a class="project-card"
         href="{{ '/projects/submersible-xrp/' | relative_url }}">

        <div class="image-wrapper">
          <img
            class="project-image"
            src="{{ '/assets/images/submersible.jpeg' | relative_url }}"
            alt="Submersible XRP underwater robot">
        </div>

        <div class="project-info">
          <div>
            <h3>Submersible</h3>
          </div>
          <span class="project-year">2026</span>
        </div>

      </a>

      <!-- 3. SMARTSWEEP -->

      <a class="project-card"
         href="{{ '/projects/smartsweep/' | relative_url }}">

        <div class="image-wrapper">
          <img
            class="project-image"
            src="{{ '/assets/images/smartsweep.jpeg' | relative_url }}"
            alt="SmartSweep mechanical prototype">
        </div>

        <div class="project-info">
          <div>
            <h3>SmartSweep</h3>
          </div>
          <span class="project-year">2026</span>
        </div>

      </a>

      <!-- 4. AR KART -->

      <a class="project-card"
         href="{{ '/projects/ar-kart/' | relative_url }}">

        <div class="image-wrapper">
          <img
            class="project-image"
            src="{{ '/assets/images/ar-kart.png' | relative_url }}"
            alt="AR Kart RC car prototype">
        </div>

        <div class="project-info">
          <div>
            <h3>AR Kart</h3>
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

      <a href="#about">
        About
      </a>

      <a href="{{ '/projects/' | relative_url }}">
        Projects
      </a>

      <a href="{{ '/cv/' | relative_url }}">
        CV
      </a>

    </div>

  </footer>

</div>
