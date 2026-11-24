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

/* ===== GOVERNING BALANCES ===== */

.heat-balances {
  width: 100%;
  max-width: 800px;
  margin: 24px auto;
}

.heat-balance {
  display: grid;
  grid-template-columns: 32% minmax(0, 1fr);
  align-items: center;
  gap: 30px;
  padding: 24px 0;
  border-bottom: 1px solid #e0e3e5;
}

.heat-balance:last-child {
  border-bottom: none;
}

.heat-diagram {
  width: 100%;
  max-width: 240px;
  margin: 0 auto;
}

.heat-diagram svg {
  display: block;
  width: 100%;
  height: auto;
}

.heat-balance-content {
  text-align: center;
  min-width: 0;
}

.heat-balance-label {
  display: block;
  font-size: 12px;
  font-weight: 600;
  letter-spacing: 1.2px;
  text-transform: uppercase;
  margin-bottom: 16px;
}

.heat-balance-formula {
  font-family: Georgia, "Times New Roman", serif;
  font-size: 23px;
  line-height: 1.8;
  color: #333;
  background: transparent;
  border: none;
  padding: 0;
  margin: 0;
}

.heat-mass-label {
  color: #64849b;
}

.heat-energy-label {
  color: #c47c62;
}

.heat-entropy-label {
  color: #b69b6a;
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

  .heat-balance {
  grid-template-columns: 1fr;
  gap: 14px;
  padding: 22px 0;
}

.heat-diagram {
  max-width: 190px;
}

.heat-balance-label {
  font-size: 11px;
  margin-bottom: 12px;
}

.heat-balance-formula {
  font-size: 18px;
}
</style>

<div class="heat-page">

  <!-- ===== PROJECT OVERVIEW ===== -->

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

  <h2>Project Overview</h2>

  <p>
    This project investigated heat transfer between two water
    streams in a compact plate heat exchanger, examining how
    flow configuration and operating conditions affect
    thermal performance.
  </p>

  <p>
    The experimental setup consisted of two independent
    circulation loops supplying hot and cold water.
    Pumps circulated water through the exchanger, while
    thermometers and a thermocouple measured inlet and
    outlet temperatures.
  </p>

  <p>
    Heat was transferred through the exchanger walls without
    mixing the fluids, allowing us to apply steady-flow
    energy balances and analyze entropy generation
    in a real engineering system.
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

  <!-- ===== VIDEO ===== -->

  <section>
  <h2>Experimental Demonstration</h2>

  <figure class="heat-video">
    <video controls playsinline preload="metadata">
      <source
        src="{{ '/assets/videos/heat_exchanger.mp4' | relative_url }}"
        type="video/mp4"
      >
    </video>

    <figcaption>
      Video 1. Heat exchanger in operation.
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

<section id="governing-balances">

  <h2>Governing Balances</h2>

  <div class="heat-balances">

    <!-- ===== 01. CONSERVATION OF MASS ===== -->

    <div class="heat-balance">

      <div class="heat-diagram">

        <svg viewBox="0 0 160 110"
             xmlns="http://www.w3.org/2000/svg"
             role="img"
             aria-label="Mass flow through a control volume">

          <!-- Control volume -->

          <rect x="48" y="18"
                width="64" height="70"
                rx="3"
                fill="#64849b"
                fill-opacity="0.08"
                stroke="#64849b"
                stroke-dasharray="4 3"/>

          <!-- Flow arrows -->

          <path d="M5 53 H62
                   M98 53 H155
                   M53 47 L62 53 L53 59
                   M146 47 L155 53 L146 59"
                stroke="#64849b"
                stroke-width="2.2"
                stroke-linecap="round"
                stroke-linejoin="round"
                fill="none"/>

          <!-- Labels -->

          <text x="24" y="40"
                font-size="11"
                fill="#555"
                text-anchor="middle">
            ṁ in
          </text>

          <text x="136" y="40"
                font-size="11"
                fill="#555"
                text-anchor="middle">
            ṁ out
          </text>

          <text x="80" y="103"
                font-size="10"
                fill="#888"
                text-anchor="middle">
            Control volume
          </text>

        </svg>

      </div>

      <div class="heat-balance-content">

        <span class="heat-balance-label heat-mass-label">
          01 — Conservation of Mass
        </span>

        <div class="heat-balance-formula">
          ṁ<sub>in</sub> = ṁ<sub>out</sub>
        </div>

      </div>

    </div>

    <!-- ===== 02. CONSERVATION OF ENERGY ===== -->

    <div class="heat-balance">

      <div class="heat-diagram">

        <svg viewBox="0 0 160 110"
             xmlns="http://www.w3.org/2000/svg"
             role="img"
             aria-label="Heat transfer between hot and cold streams">

          <!-- Hot stream -->

          <rect x="12" y="17"
                width="136" height="28"
                rx="4"
                fill="#c47c62"
                fill-opacity="0.14"/>

          <!-- Cold stream -->

          <rect x="12" y="65"
                width="136" height="28"
                rx="4"
                fill="#64849b"
                fill-opacity="0.15"/>

          <!-- Hot flow arrow -->

          <path d="M23 31 H135
                   L127 25
                   M135 31 L127 37"
                stroke="#c47c62"
                stroke-width="2.5"
                stroke-linecap="round"
                stroke-linejoin="round"
                fill="none"/>

          <!-- Cold flow arrow -->

          <path d="M135 79 H23
                   L31 73
                   M23 79 L31 85"
                stroke="#64849b"
                stroke-width="2.5"
                stroke-linecap="round"
                stroke-linejoin="round"
                fill="none"/>

          <!-- Heat transfer arrows -->

          <path d="M45 43 V63
                   L41 58
                   M45 63 L49 58

                   M80 43 V63
                   L76 58
                   M80 63 L84 58

                   M115 43 V63
                   L111 58
                   M115 63 L119 58"
                stroke="#b69b6a"
                stroke-width="1.6"
                stroke-linecap="round"
                stroke-linejoin="round"
                fill="none"/>

          <!-- Labels -->

          <text x="80" y="11"
                font-size="10"
                fill="#c47c62"
                text-anchor="middle">
            HOT STREAM
          </text>

          <text x="80" y="105"
                font-size="10"
                fill="#64849b"
                text-anchor="middle">
            COLD STREAM
          </text>

        </svg>

      </div>

      <div class="heat-balance-content">

        <span class="heat-balance-label heat-energy-label">
          02 — Conservation of Energy
        </span>

        <div class="heat-balance-formula">
          ṁ<sub>h</sub>c<sub>p</sub>ΔT<sub>h</sub>
          +
          ṁ<sub>c</sub>c<sub>p</sub>ΔT<sub>c</sub>
          = 0
        </div>

      </div>

    </div>

    <!-- ===== 03. ENTROPY GENERATION ===== -->

    <div class="heat-balance">

      <div class="heat-diagram">

        <svg viewBox="0 0 160 110"
             xmlns="http://www.w3.org/2000/svg"
             role="img"
             aria-label="Illustrative temperature profiles and finite temperature difference">

          <!-- Graph axes -->

          <path d="M22 10 V91 H150"
                stroke="#aaa"
                stroke-width="1.2"
                fill="none"/>

          <!-- Hot temperature curve -->

          <path d="M28 23
                   C65 30 100 41 143 49"
                stroke="#c47c62"
                stroke-width="2.5"
                stroke-linecap="round"
                fill="none"/>

          <!-- Cold temperature curve -->

          <path d="M28 62
                   C65 69 100 80 143 88"
                stroke="#64849b"
                stroke-width="2.5"
                stroke-linecap="round"
                fill="none"/>

          <!-- Temperature difference -->

          <path d="M85 37 V75
                   M81 42 L85 37 L89 42
                   M81 70 L85 75 L89 70"
                stroke="#b69b6a"
                stroke-width="1.5"
                stroke-linecap="round"
                stroke-linejoin="round"
                fill="none"/>

          <!-- Labels -->

          <text x="94" y="59"
                font-size="12"
                fill="#b69b6a">
            ΔT
          </text>

          <text x="12" y="14"
                font-size="10"
                fill="#777">
            T
          </text>

          <text x="148" y="103"
                font-size="10"
                fill="#777">
            x
          </text>

        </svg>

      </div>

      <div class="heat-balance-content">

        <span class="heat-balance-label heat-entropy-label">
          03 — Entropy Generation
        </span>

        <div class="heat-balance-formula">
          Ṡ<sub>gen</sub>
          =
          ṁ<sub>h</sub>Δs<sub>h</sub>
          +
          ṁ<sub>c</sub>Δs<sub>c</sub>
          ≥ 0
        </div>

      </div>

    </div>

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
