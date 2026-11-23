---
layout: project
title: Heat Exchanger System Analysis
permalink: /projects/heat-exchanger/
description: Thermodynamics Coursework Project
technologies: [Thermodynamics, Energy Balance, Heat Transfer, Entropy Analysis, Experimental Testing]
---

<style>
/* ===== HEAT EXCHANGER PAGE ===== */

.heat-page {
  width: 85vw;
  max-width: 900px;
  margin-left: 50%;
  transform: translateX(-50%);
  padding: 20px 0 65px;
  font-family: "Helvetica Neue", Arial, sans-serif;
  color: #222;
  text-align: center;
  box-sizing: border-box;
}

.heat-page * {
  box-sizing: border-box;
}

.heat-page h1,
.heat-page h2 {
  font-family: Georgia, "Times New Roman", serif;
  color: #171717;
  letter-spacing: -0.04em;
}

.heat-page h1 {
  font-size: clamp(42px, 5vw, 58px);
  line-height: 1.1;
  margin: 0 0 16px;
}

.heat-page h2 {
  font-size: clamp(30px, 3.5vw, 39px);
  font-weight: 400;
  margin: 0 0 18px;
}

.heat-page h3 {
  font-size: 19px;
  font-weight: 600;
  margin: 24px 0 14px;
}

.heat-page p {
  max-width: 800px;
  margin: 0 auto 16px;
  font-size: 16px;
  line-height: 1.85;
  color: #444;
}

.heat-page section {
  margin-bottom: 46px;
}

/* ===== METADATA ===== */

.heat-meta {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 20px;
  padding: 18px 0;
  margin: 24px 0 28px;
  border-top: 1px solid #e5e5e5;
  border-bottom: 1px solid #e5e5e5;
}

.heat-meta-label {
  display: block;
  font-size: 11px;
  font-weight: 700;
  letter-spacing: 1.5px;
  text-transform: uppercase;
  color: #999;
  margin-bottom: 5px;
}

.heat-meta-value {
  font-size: 14px;
  color: #333;
}

/* ===== IMAGES ===== */

.heat-page figure {
  margin: 24px auto;
}

.heat-page img {
  display: block;
  width: 100%;
  height: auto;
  border-radius: 5px;
}

.heat-hero {
  width: 80%;
  max-width: 650px;
}

.heat-page figcaption {
  margin-top: 9px;
  font-size: 12px;
  line-height: 1.6;
  color: #888;
}

/* ===== VIDEO ===== */

.heat-video {
  width: 75%;
  max-width: 620px;
  margin: 26px auto;
}

.heat-video video {
  display: block;
  width: 100%;
  height: auto;
  max-height: 420px;
  object-fit: contain;
  border-radius: 6px;
  background: #111;
}

/* ===== EQUATIONS ===== */

.heat-equation {
  max-width: 800px;
  margin: 20px auto;
  padding: 22px 18px;
  background: #f6f6f5;
  border-radius: 5px;
  font-size: 18px;
  line-height: 1.8;
  overflow-x: auto;
}

.heat-equation-label {
  display: block;
  font-size: 11px;
  font-weight: 700;
  letter-spacing: 1.3px;
  text-transform: uppercase;
  color: #888;
  margin-bottom: 10px;
}

/* ===== ASSUMPTIONS ===== */

.heat-assumptions {
  max-width: 760px;
  margin: 22px auto;
  text-align: left;
}

.heat-assumption {
  padding: 13px 0;
  border-bottom: 1px solid #e8e8e8;
  font-size: 15px;
  color: #444;
}

/* ===== FLOW COMPARISON ===== */

.heat-comparison {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 20px;
  max-width: 800px;
  margin: 25px auto;
}

.heat-flow-card {
  padding: 24px 22px;
  border: 1px solid #e4e7e5;
  background: #f7f8f7;
  border-radius: 7px;
  text-align: center;
}

.heat-flow-card h3 {
  margin: 0 0 14px;
  font-size: 18px;
}

.heat-flow-card p {
  font-size: 14px;
  line-height: 1.7;
  margin: 12px auto 0;
}

.heat-flow-lines {
  padding: 12px 0;
  font-size: 15px;
  font-weight: 600;
}

.heat-hot {
  color: #bd765e;
}

.heat-cold {
  color: #5b849e;
}

/* ===== MOBILE ===== */

@media (max-width: 700px) {
  .heat-page {
    width: calc(100% - 36px);
  }

  .heat-meta {
    gap: 10px;
  }

  .heat-meta-value {
    font-size: 12px;
  }

  .heat-hero,
  .heat-video {
    width: 100%;
  }

  .heat-comparison {
    grid-template-columns: 1fr;
  }

  .heat-equation {
    font-size: 15px;
  }
}
</style>

<div class="heat-page">

  <!-- ===== INTRODUCTION ===== -->

  <section>
    <h1>Heat Exchanger System Analysis</h1>

    <div class="heat-meta">
      <div>
        <span class="heat-meta-label">Course</span>
        <span class="heat-meta-value">Thermodynamics</span>
      </div>

      <div>
        <span class="heat-meta-label">Focus</span>
        <span class="heat-meta-value">Heat Transfer</span>
      </div>

      <div>
        <span class="heat-meta-label">System</span>
        <span class="heat-meta-value">Plate Heat Exchanger</span>
      </div>
    </div>

    <p>
      This project investigated how thermal energy
      is transferred between two water streams
      in a compact plate heat exchanger.
      We studied how flow configuration and
      operating conditions affect thermal performance.
    </p>

    <p>
      The experiment connected steady-flow energy
      balances and entropy generation to the behavior
      of a real engineering system.
    </p>

    <figure class="heat-hero">
      <img
        src="{{ '/assets/images/heat-exchanger.jpg' | relative_url }}"
        alt="Heat exchanger experimental setup"
      >
      <figcaption>
        Figure 1. Experimental heat exchanger system.
      </figcaption>
    </figure>
  </section>

  <!-- ===== SYSTEM DESCRIPTION ===== -->

  <section>
    <h2>System Description</h2>

    <p>
      The setup consisted of a plate heat exchanger
      connected to two independent water circulation
      loops. One supplied hot water from a heated
      reservoir, while the other supplied cold water
      from an insulated reservoir.
    </p>

    <p>
      Each loop used a pump to circulate water.
      Temperatures were measured at the inlet and
      outlet using thermometers and a thermocouple.
      Heat passed through the exchanger walls
      without the two streams mixing.
    </p>
  </section>

  <!-- ===== VIDEO ===== -->

  <section>
    <h2>Experimental Setup in Operation</h2>

    <p>
      The video shows the physical heat exchanger
      setup used to investigate heat transfer
      between the hot and cold water loops.
    </p>

    <figure class="heat-video">
      <video controls playsinline preload="metadata">
        <source
          src="{{ '/assets/videos/heat-exchanger.mp4' | relative_url }}"
          type="video/mp4"
        >
        Your browser does not support video playback.
      </video>

      <figcaption>
        Video 1. Heat exchanger experimental setup
        during operation.
      </figcaption>
    </figure>
  </section>

  <!-- ===== THERMODYNAMIC MODELING ===== -->

  <section>
    <h2>Thermodynamic Modeling</h2>

    <p>
      We modeled the heat exchanger as a steady-flow
      control volume and applied conservation of
      mass and energy to both water streams.
    </p>

    <div class="heat-assumptions">
      <div class="heat-assumption">
        Steady-state operation
      </div>

      <div class="heat-assumption">
        Incompressible liquid water
      </div>

      <div class="heat-assumption">
        Negligible kinetic and potential energy changes
      </div>

      <div class="heat-assumption">
        No shaft work within the heat exchanger
      </div>

      <div class="heat-assumption">
        Negligible heat transfer to the surroundings
      </div>
    </div>
  </section>

  <!-- ===== GOVERNING BALANCES ===== -->

  <section>
    <h2>Governing Balances</h2>

    <p>
      Conservation of mass requires the mass
      flow rate entering each stream to equal
      the mass flow rate leaving it.
    </p>

    <div class="heat-equation">
      <span class="heat-equation-label">
        Conservation of Mass
      </span>

      ṁ<sub>in</sub> = ṁ<sub>out</sub>
    </div>

    <p>
      Assuming negligible heat loss to the surroundings,
      the energy lost by the hot water equals the
      energy gained by the cold water.
    </p>

    <div class="heat-equation">
      <span class="heat-equation-label">
        Steady-Flow Energy Balance
      </span>

      ṁ<sub>h</sub>c<sub>p</sub>
      (T<sub>h,out</sub> − T<sub>h,in</sub>)
      +
      ṁ<sub>c</sub>c<sub>p</sub>
      (T<sub>c,out</sub> − T<sub>c,in</sub>)
      = 0
    </div>

    <p>
      We also considered entropy generation
      associated with irreversible heat transfer
      across a finite temperature difference.
    </p>

    <div class="heat-equation">
      <span class="heat-equation-label">
        Entropy Generation
      </span>

      Ṡ<sub>gen</sub> =
      ṁ<sub>h</sub>(s<sub>h,out</sub> − s<sub>h,in</sub>)
      +
      ṁ<sub>c</sub>(s<sub>c,out</sub> − s<sub>c,in</sub>)
      ≥ 0
    </div>
  </section>

  <!-- ===== FLOW CONFIGURATIONS ===== -->

  <section>
    <h2>Parallel Flow vs. Counterflow</h2>

    <p>
      We examined two flow configurations to
      understand how the direction of the water
      streams affects heat transfer.
    </p>

    <div class="heat-comparison">

      <div class="heat-flow-card">
        <h3>Parallel Flow</h3>

        <div class="heat-flow-lines">
          <div class="heat-hot">Hot Water →</div>
          <div class="heat-cold">Cold Water →</div>
        </div>

        <p>
          Both streams travel in the same direction.
          The temperature difference is greatest
          near the inlet and decreases along
          the exchanger.
        </p>
      </div>

      <div class="heat-flow-card">
        <h3>Counterflow</h3>

        <div class="heat-flow-lines">
          <div class="heat-hot">Hot Water →</div>
          <div class="heat-cold">Cold Water ←</div>
        </div>

        <p>
          The streams travel in opposite directions,
          maintaining a more uniform temperature
          difference and generally allowing
          greater heat transfer effectiveness.
        </p>
      </div>

    </div>

    <p>
      Counterflow operation can allow the cold
      outlet temperature to approach the hot
      inlet temperature more closely than
      parallel-flow operation.
    </p>

    <p>
      We also considered how changes in flow rate
      influence heat transfer. Higher flow rates
      can increase the heat transfer rate while
      reducing the temperature change experienced
      by an individual stream.
    </p>
  </section>

  <!-- ===== ENGINEERING RELEVANCE ===== -->

  <section>
    <h2>Engineering Relevance</h2>

    <p>
      Heat exchangers are used in HVAC systems,
      power generation, automotive cooling,
      and industrial processing.
    </p>

    <p>
      This project helped connect thermodynamic
      theory with experimental equipment and
      showed how flow arrangement and operating
      conditions influence energy transfer
      and system efficiency.
    </p>
  </section>

</div>
