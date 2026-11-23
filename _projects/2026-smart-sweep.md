---
layout: project
title: SmartSweep
permalink: /projects/smart-sweep/
description: Spotted Lanternfly Removal — Mechanical Design and Prototyping
technologies: [Fusion 360, 3D Printing, Rapid Prototyping, Mechanical Design, DC Motor Integration, Testing]
---

<style>
/* ===== SMARTSWEEP PROJECT PAGE ===== */

.smart-page {
  width: 85vw;
  max-width: 900px;
  margin-left: 50%;
  transform: translateX(-50%);
  padding: 20px 0 75px;
  font-family: "Helvetica Neue", Arial, sans-serif;
  color: #222;
  text-align: center;
  box-sizing: border-box;
}

.smart-page * {
  box-sizing: border-box;
}

/* ===== TYPOGRAPHY ===== */

.smart-page .smart-title {
  font-family: Georgia, "Times New Roman", serif;
  font-size: clamp(40px, 5vw, 54px);
  font-weight: 700;
  letter-spacing: -0.045em;
  line-height: 1.12;
  margin: 0 0 16px;
  color: #171717;
}

.smart-page h2 {
  font-family: Georgia, "Times New Roman", serif;
  font-size: clamp(29px, 3vw, 38px);
  font-weight: 400;
  letter-spacing: -0.035em;
  line-height: 1.25;
  margin: 0 0 18px;
  color: #171717;
}

.smart-page h3 {
  font-family: "Helvetica Neue", Arial, sans-serif;
  font-size: 21px;
  font-weight: 500;
  letter-spacing: -0.02em;
  margin: 26px 0 14px;
}

.smart-page p {
  font-size: 16px;
  line-height: 1.85;
  color: #444;
  margin: 0 0 14px;
}

.smart-page section {
  margin-bottom: 45px;
}

.smart-text {
  max-width: 800px;
  margin: 0 auto;
}

/* ===== METADATA ===== */

.smart-meta {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 20px;
  align-items: start;
  width: 100%;
  padding: 20px 0;
  margin: 0 auto 28px;
  border-top: 1px solid #e6e6e6;
  border-bottom: 1px solid #e6e6e6;
}

.smart-meta-item {
  min-width: 0;
}

.smart-meta-heading {
  font-size: 11px;
  font-weight: 700;
  letter-spacing: 1.5px;
  text-transform: uppercase;
  color: #999;
  margin-bottom: 9px;
}

.smart-meta-value {
  font-size: 14px;
  line-height: 1.6;
  color: #333;
}

.smart-report-link {
  color: #333;
  text-decoration: none;
  border-bottom: 1px solid #aaa;
  padding-bottom: 3px;
}

.smart-report-link:hover {
  color: #111;
  border-color: #111;
}

/* ===== IMAGES ===== */

.smart-page figure {
  margin: 0;
  min-width: 0;
}

.smart-page img {
  display: block;
  width: 100%;
  height: auto;
  margin: 0 auto;
  border-radius: 3px;
  box-shadow: none;
}

.smart-page figcaption {
  font-size: 12px;
  line-height: 1.65;
  color: #888;
  margin-top: 8px;
}

.smart-hero {
  width: 70%;
  max-width: 630px;
  margin: 24px auto !important;
}

.smart-gallery {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 24px;
  width: 100%;
  margin: 24px auto;
  align-items: start;
}

.smart-gallery figure {
  width: 100%;
}

.smart-gallery img {
  width: 100%;
  height: 285px;
  object-fit: contain;
}

.smart-full {
  width: 100%;
  margin: 24px auto !important;
}

/* ===== METRIC CARDS ===== */

.smart-specs {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 18px;
  margin: 24px 0;
}

.smart-spec {
  background: #f7f7f6;
  padding: 25px 14px;
  border-radius: 3px;
}

.smart-spec-number {
  font-size: 30px;
  font-weight: 600;
  letter-spacing: -0.04em;
  margin-bottom: 7px;
}

.smart-spec-label {
  font-size: 12px;
  color: #777;
  line-height: 1.6;
}

/* ===== TEST RESULTS ===== */

.smart-results {
  max-width: 800px;
  margin: 20px auto 28px;
  text-align: left;
  border-top: 1px solid #e8e8e8;
}

.smart-result-row {
  display: grid;
  grid-template-columns: 1fr 2fr;
  gap: 18px;
  padding: 15px 0;
  border-bottom: 1px solid #e8e8e8;
}

.smart-result-label {
  font-size: 13px;
  font-weight: 600;
  color: #333;
}

.smart-result-value {
  font-size: 14px;
  line-height: 1.65;
  color: #555;
}

/* ===== REPORT LINK ===== */

.smart-report-card {
  max-width: 700px;
  margin: 25px auto;
  padding: 28px 24px;
  background: #f7f7f6;
  border-radius: 3px;
}

.smart-report-card p {
  font-size: 14px;
}

.smart-report-card a {
  display: inline-block;
  margin-top: 5px;
  color: #222;
  font-size: 15px;
  font-weight: 600;
  text-decoration: none;
  border-bottom: 1px solid #888;
  padding-bottom: 4px;
}

/* ===== MOBILE ===== */

@media (max-width: 700px) {
  .smart-page {
    width: calc(100% - 36px);
    padding: 20px 0 65px;
  }

  .smart-page section {
    margin-bottom: 35px;
  }

  .smart-meta {
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 22px 14px;
  }

  .smart-meta-value {
    font-size: 13px;
  }

  .smart-hero {
    width: 100%;
  }

  .smart-gallery,
  .smart-specs {
    grid-template-columns: 1fr;
  }

  .smart-gallery img {
    height: auto;
  }

  .smart-result-row {
    grid-template-columns: 1fr;
    gap: 5px;
  }

  .smart-page p {
    font-size: 15px;
  }
}
</style>

<div class="smart-page">

  <!-- ===== TITLE ===== -->

  <h1 class="smart-title">SmartSweep</h1>

  <!-- ===== OVERVIEW ===== -->

  <section id="overview">

    <div class="smart-meta">

      <div class="smart-meta-item">
        <div class="smart-meta-heading">Role</div>
        <div class="smart-meta-value">
          Project Lead &amp; Mechanical Design
        </div>
      </div>

      <div class="smart-meta-item">
        <div class="smart-meta-heading">Year</div>
        <div class="smart-meta-value">
          Spring 2026
        </div>
      </div>

      <div class="smart-meta-item">
        <div class="smart-meta-heading">Team</div>
        <div class="smart-meta-value">
          Spotted... then Stopped
        </div>
      </div>

      <div class="smart-meta-item">
        <div class="smart-meta-heading">Documentation</div>
        <div class="smart-meta-value">
          <a
            class="smart-report-link"
            href="https://docs.google.com/document/d/1K4rZF0i-Lw44lrSVzpyYk6Z6Sbv8mkQhzqhPHqws2ZQ/edit"
            target="_blank"
            rel="noopener noreferrer"
          >
            Client Report ↗
          </a>
        </div>
      </div>

    </div>

    <h2>Project Overview</h2>

    <div class="smart-text">
      <p>
        SmartSweep was developed as part of Cornell's MAE 2250
        Open Design Project to address spotted lanternfly
        contamination in vineyards. Our team designed and
        prototyped a mechanical brush system intended to
        remove lanternflies from grapevines before harvesting,
        reducing the risk of insects entering the grape yield.
      </p>

      <p>
        As project lead, I helped guide the design process
        from initial concepts through prototyping and testing.
        I worked on the mechanical design of the brush
        assembly, shaft geometry, and motor integration,
        using Fusion 360 and 3D printing to develop and
        improve the prototype.
      </p>
    </div>

    <figure class="smart-hero">
      <img
        src="{{ '/assets/images/smartsweep.png' | relative_url }}"
        alt="SmartSweep spotted lanternfly removal prototype"
      >
      <figcaption>
        Figure 1. SmartSweep spotted lanternfly removal system.
      </figcaption>
    </figure>

  </section>

  <!-- ===== PROBLEM ===== -->

  <section id="problem">

    <h2>Problem &amp; Design Objective</h2>

    <div class="smart-text">
      <p>
        Spotted lanternflies can enter mechanical grape
        harvesters along with harvested fruit, potentially
        contaminating the yield. Our client-focused design
        challenge was to develop a mechanism that could
        remove insects from vines before grape collection
        without damaging the vines or prematurely
        dislodging grapes.
      </p>

      <p>
        We proposed a front-mounted attachment for
        existing harvesting equipment, using rotating
        brushes positioned to sweep insects away from
        the vines. The design needed to be adjustable,
        effective at removing insects, and practical
        to assemble and maintain.
      </p>
    </div>

  </section>

  <!-- ===== CONCEPT DEVELOPMENT ===== -->

  <section id="concept">

    <h2>Concept Development</h2>

    <div class="smart-text">
      <p>
        Our initial concept used two rotating cylindrical
        brushes mounted to an adjustable frame. Inspired
        by the motion of car-wash brushes, the system
        would sweep along the vine area as the harvester
        moved forward.
      </p>

      <p>
        Brush height, bristle length, and spacing were
        important considerations. The mechanism needed
        sufficient contact to remove insects while
        limiting unwanted contact with grapes and vines.
      </p>
    </div>

    <div class="smart-gallery">

      <figure>
        <img
          src="{{ '/assets/images/mockup.png' | relative_url }}"
          alt="Front view of the initial spinning brush concept"
          loading="lazy"
        >
        <figcaption>
          Figure 2. Initial brush concept — front view.
        </figcaption>
      </figure>

      <figure>
        <img
          src="{{ '/assets/images/mockup_back.png' | relative_url }}"
          alt="Rear view of the initial spinning brush concept"
          loading="lazy"
        >
        <figcaption>
          Figure 3. Initial brush concept — rear view.
        </figcaption>
      </figure>

    </div>

  </section>

  <!-- ===== BRUSH TESTING ===== -->

  <section id="brush-testing">

    <h2>Brush Design &amp; Testing</h2>

    <div class="smart-text">
      <p>
        We built a functional prototype to evaluate
        whether rotating strip brushes could effectively
        remove objects from a cylindrical surface.
        Testing also helped us compare brush lengths
        and identify changes needed before the final
        assembly.
      </p>

      <p>
        For the removal test, five sticky-note rings
        were attached to a rod to represent objects
        that needed to be dislodged. We operated
        the brush for approximately ten revolutions
        and recorded how many rings were removed
        across three trials.
      </p>
    </div>

    <div class="smart-gallery">

      <figure>
        <img
          src="{{ '/assets/images/small_brush.png' | relative_url }}"
          alt="Prototype using shorter brush bristles"
          loading="lazy"
        >
        <figcaption>
          Figure 4. Shorter brush configuration.
        </figcaption>
      </figure>

      <figure>
        <img
          src="{{ '/assets/images/large_brush.png' | relative_url }}"
          alt="Prototype using longer brush bristles"
          loading="lazy"
        >
        <figcaption>
          Figure 5. Longer brush configuration.
        </figcaption>
      </figure>

    </div>

    <div class="smart-results">
      <div class="smart-result-row">
        <div class="smart-result-label">Trial 1</div>
        <div class="smart-result-value">3 of 5 rings removed</div>
      </div>
      <div class="smart-result-row">
        <div class="smart-result-label">Trial 2</div>
        <div class="smart-result-value">5 of 5 rings removed</div>
      </div>
      <div class="smart-result-row">
        <div class="smart-result-label">Trial 3</div>
        <div class="smart-result-value">5 of 5 rings removed</div>
      </div>
    </div>

    <div class="smart-text">
      <p>
        The brush passed our functional test criteria,
        but the shorter bristles did not consistently
        reach objects farther from the shaft. Based
        on these observations, we selected longer
        brushes for the next prototype iteration.
      </p>
    </div>

  </section>

  <!-- ===== SHAFT DESIGN ===== -->

  <section id="shaft-design">

    <h2>Shaft Design &amp; Assembly Iterations</h2>

    <div class="smart-text">
      <p>
        Another challenge was designing the shaft slots
        to hold the strip brushes securely while allowing
        them to be inserted and replaced without damaging
        the printed components.
      </p>

      <p>
        Our first printed shaft had slots that were too
        tight, requiring excessive insertion force and
        causing damage during assembly. We revised
        the geometry by increasing the slot length
        by 1.27 inches and smoothing the edges.
      </p>
    </div>

    <div class="smart-gallery">

      <figure>
        <img
          src="{{ '/assets/images/broken.png' | relative_url }}"
          alt="Damaged shaft slots from the first prototype"
          loading="lazy"
        >
        <figcaption>
          Figure 6. First shaft iteration with damaged slots.
        </figcaption>
      </figure>

      <figure>
        <img
          src="{{ '/assets/images/large_slot.png' | relative_url }}"
          alt="Redesigned shaft with larger brush slots"
          loading="lazy"
        >
        <figcaption>
          Figure 7. Revised shaft with improved slot geometry.
        </figcaption>
      </figure>

    </div>

    <div class="smart-text">
      <p>
        We evaluated the clearance by inserting the
        brushes and measuring the remaining gap using
        folded paper strips. The second print allowed
        smooth insertion with approximately one sheet
        of paper clearance, providing a better balance
        between brush retention and ease of assembly.
      </p>
    </div>

  </section>

  <!-- ===== MOTOR AND TORQUE ===== -->

  <section id="motor">

    <h2>Motor Selection &amp; Torque Testing</h2>

    <div class="smart-text">
      <p>
        To estimate the torque required to rotate the
        brush shaft, we applied increasing weights to
        a 1.75 cm crank arm attached to the shaft.
        The mechanism did not rotate with a 50 g load,
        but rotation was achieved with a 100 g load.
      </p>

      <p>
        This gave us an estimated required torque of
        approximately 0.02 N·m, which helped guide
        motor selection for the functional prototype.
      </p>
    </div>

    <div class="smart-gallery">

      <figure>
        <img
          src="{{ '/assets/images/gears.png' | relative_url }}"
          alt="Earlier gear system prototypes"
          loading="lazy"
        >
        <figcaption>
          Figure 8. Earlier gear system iterations.
        </figcaption>
      </figure>

      <figure>
        <img
          src="{{ '/assets/images/torque.png' | relative_url }}"
          alt="Torque testing setup"
          loading="lazy"
        >
        <figcaption>
          Figure 9. Torque test setup.
        </figcaption>
      </figure>

    </div>

    <div class="smart-specs">
      <div class="smart-spec">
        <div class="smart-spec-number">1.75 cm</div>
        <div class="smart-spec-label">Crank arm length</div>
      </div>

      <div class="smart-spec">
        <div class="smart-spec-number">100 g</div>
        <div class="smart-spec-label">Load producing rotation</div>
      </div>

      <div class="smart-spec">
        <div class="smart-spec-number">0.02 N·m</div>
        <div class="smart-spec-label">Estimated torque requirement</div>
      </div>
    </div>

  </section>

  <!-- ===== RESULTS ===== -->

  <section id="results">

    <h2>Final Prototype &amp; Results</h2>

    <div class="smart-text">
      <p>
        Through iterative testing, we improved the
        brush configuration and shaft assembly,
        addressing issues with bristle reach,
        insertion force, and component fit.
        The functional prototype demonstrated
        the feasibility of using rotating brushes
        to dislodge objects from a cylindrical
        surface.
      </p>

      <p>
        The project received runner-up recognition
        for Outstanding Problem/Solution.
        Further development would be needed to
        evaluate performance on real grapevines
        and integrate the system with a harvester.
      </p>
    </div>

    <div class="smart-report-card">
      <h3>Final Client Report</h3>

      <p>
        The full report documents our design
        process, prototype development, testing,
        and recommendations.
      </p>

      <a
        href="https://docs.google.com/document/d/1K4rZF0i-Lw44lrSVzpyYk6Z6Sbv8mkQhzqhPHqws2ZQ/edit"
        target="_blank"
        rel="noopener noreferrer"
      >
        View Full Client Report ↗
      </a>
    </div>

  </section>

</div>
