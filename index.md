---
layout: default
title: Home
---

<style>
/* HOMEPAGE DESIGN */

.homepage {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 30px;
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

.homepage .hero {
  padding: 110px 0 95px;
}

.homepage .eyebrow {
  font-size: 13px;
  font-weight: 600;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: #777;
  margin-bottom: 24px;
}

.homepage h1 {
  font-size: clamp(46px, 7vw, 92px);
  font-weight: 600;
  letter-spacing: -0.065em;
  line-height: 1.05;
  margin: 0 0 30px;
}

.homepage .hero-description {
  max-width: 650px;
  font-size: 20px;
  line-height: 1.65;
  color: #666;
}

.homepage .hero-links {
  display: flex;
  gap: 25px;
  margin-top: 35px;
  flex-wrap: wrap;
}

.homepage .hero-links a {
  font-size: 15px;
  font-weight: 600;
  padding-bottom: 5px;
  border-bottom: 1px solid #222;
  transition: opacity 0.2s;
}

.homepage .hero-links a:hover {
  opacity: 0.5;
}

/* SECTION HEADERS */

.homepage .section-heading {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 22px 0;
  border-top: 1px solid #ddd;
  margin-bottom: 35px;
}

.homepage .section-heading h2 {
  font-size: 16px;
  font-weight: 600;
  margin: 0;
}

.homepage .section-heading span {
  font-size: 13px;
  color: #888;
}

/* PROJECT GRID */

.homepage .project-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 65px 25px;
}

.homepage .project-card {
  display: block;
}

.homepage .project-image {
  width: 100%;
  aspect-ratio: 4 / 3;
  object-fit: cover;
  border-radius: 8px;
  background: #f1f1f1;
  display: block;
  transition: transform 0.35s ease;
}

.homepage .image-wrapper {
  overflow: hidden;
  border-radius: 8px;
}

.homepage .project-card:hover .project-image {
  transform: scale(1.035);
}

.homepage .project-info {
  display: flex;
  justify-content: space-between;
  gap: 15px;
  align-items: flex-start;
  padding-top: 17px;
}

.homepage .project-info h3 {
  font-size: 22px;
  font-weight: 600;
  letter-spacing: -0.5px;
  margin: 0 0 7px;
}

.homepage .project-info p {
  font-size: 14px;
  color: #777;
  line-height: 1.5;
  margin: 0;
}

.homepage .project-year {
  font-size: 13px;
  color: #999;
  white-space: nowrap;
}

/* ABOUT SECTION */

.homepage .about {
  margin-top: 130px;
}

.homepage .about-content {
  display: grid;
  grid-template-columns: 1fr 1.5fr;
  gap: 70px;
  padding: 15px 0 100px;
}

.homepage .about-content h2 {
  font-size: 42px;
  letter-spacing: -2px;
  line-height: 1.15;
  margin: 0;
}

.homepage .about-text {
  font-size: 18px;
  line-height: 1.8;
  color: #555;
}

.homepage .about-text p {
  margin: 0 0 22px;
}

/* FOOTER */

.homepage .portfolio-footer {
  border-top: 1px solid #ddd;
  padding: 35px 0 60px;
  display: flex;
  justify-content: space-between;
  gap: 20px;
  flex-wrap: wrap;
  font-size: 14px;
  color: #777;
}

.homepage .footer-links {
  display: flex;
  gap: 22px;
}

.homepage .footer-links a:hover {
  color: #111;
}

/* MOBILE */

@media (max-width: 700px) {
  .homepage {
    padding: 0 20px;
  }

  .homepage .hero {
    padding: 75px 0;
  }

  .homepage .hero-description {
    font-size: 17px;
  }

  .homepage .project-grid {
    grid-template-columns: 1fr;
    gap: 45px;
  }

  .homepage .about {
    margin-top: 85px;
  }

  .homepage .about-content {
    grid-template-columns: 1fr;
    gap: 25px;
  }

  .homepage .about-content h2 {
    font-size: 34px;
  }

  .homepage .about-text {
    font-size: 16px;
  }
}
</style>

<div class="homepage">

  <!-- HERO -->

  <section class="hero">

    <div class="eyebrow">
      MECHANICAL ENGINEERING · CORNELL UNIVERSITY
    </div>

    <h1>
      Hi, I'm Jenny.<br>
      I like making<br>
      things work.
    </h1>

    <p class="hero-description">
      I'm a mechanical engineering student at Cornell
      University with a passion for robotics, product
      design, and hands-on problem solving.
      I love turning ideas into real, working things.
    </p>

    <div class="hero-links">
      <a href="#projects">Explore my work ↗</a>
      <a href="#about">More about me ↗</a>
    </div>

  </section>

  <!-- PROJECTS -->

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
            <p>
              Mechanical Design · Gear Systems · Robotics
            </p>
          </div>
          <span class="project-year">2026</span>
        </div>

      </a>

      <!-- SUBMERSIBLE XRP -->

      <a class="project-card"
         href="{{ '/projects/submersible-xrp/' | relative_url }}">

        <div class="image-wrapper">
          <img class="project-image"
               src="{{ '/assets/images/submersible-xrp.jpg' | relative_url }}"
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
            <p>
              Product Development · Mechanical Design
            </p>
          </div>
          <span class="project-year">2026</span>
        </div>

      </a>

      <!-- AR KART -->

      <a class="project-card"
         href="{{ '/projects/ar-kart/' | relative_url }}">

        <div class="image-wrapper">
          <img class="project-image"
               src="{{ '/assets/images/ar-kart.jpg' | relative_url }}"
               alt="AR Kart RC car prototype">
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

  <!-- ABOUT -->

  <section id="about" class="about">

    <div class="section-heading">
      <h2>About Me</h2>
      <span>02 / Background</span>
    </div>

    <div class="about-content">

      <h2>
        Curious by nature.<br>
        Engineer by choice.
      </h2>

      <div class="about-text">

        <p>
          I'm a junior studying Mechanical Engineering
          at Cornell University, where I'm part of
          Cornell Cup Robotics.
        </p>

        <p>
          From designing gear-driven mechanisms to
          developing underwater robots, I enjoy the
          entire engineering process — designing,
          building, testing, and figuring out what
          could work better.
        </p>

        <p>
          Outside of engineering, you'll probably find
          me golfing, painting, baking, or trying
          something new.
        </p>

      </div>

    </div>

  </section>

  <!-- FOOTER -->

  <footer class="portfolio-footer">

    <span>© 2026 Jenny Wu</span>

    <div class="footer-links">
      <a href="https://www.linkedin.com/in/jenny-wu-44b5912a8/" target="_blank" rel="noopener noreferrer">
        LinkedIn
      </a>
      <a href="{{ '/assets/Resume.pdf' | relative_url }}" target="_blank">
        Resume
      </a>
      <a href="jw2774@cornell.edu">
        Email
      </a>
    </div>

  </footer>

</div>
