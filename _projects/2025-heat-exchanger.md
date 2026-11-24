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
  display: grid;
  grid-template-columns: repeat(6, minmax(0, 1fr));
  gap: 20px 18px;
  max-width: 720px;
  margin: 24px auto 8px;
  text-align: center;
}

.heat-assumption {
  grid-column: span 2;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 7px;
  padding: 4px 0;
  border: none;
  background: transparent;
}

.heat-assumption:nth-child(4) {
  grid-column: 2 / span 2;
}

.heat-assumption:nth-child(5) {
  grid-column: 4 / span 2;
}

.heat-assumption svg {
  display: block;
  width: 100%;
  max-width: 145px;
  height: auto;
  margin: 0 auto 3px;
}

.heat-assumption-title {
  font-size: 13px;
  font-weight: 600;
  color: #444;
  line-height: 1.5;
}

.heat-assumption-formula {
  font-family: Georgia, "Times New Roman", serif;
  font-size: 17px;
  color: #555;
  line-height: 1.5;
}

@media (max-width: 700px) {
  .heat-assumptions {
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 18px 12px;
  }

  .heat-assumption,
  .heat-assumption:nth-child(4),
  .heat-assumption:nth-child(5) {
    grid-column: auto;
  }

  .heat-assumption:last-child {
    grid-column: 1 / -1;
  }

  .heat-assumption svg {
    max-width: 125px;
  }

  .heat-assumption-title {
    font-size: 12px;
  }

  .heat-assumption-formula {
    font-size: 15px;
  }
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
    The heat exchanger was modeled as a steady-flow
    control volume under the following assumptions.
  </p>

  <div class="heat-assumptions">

    <!-- STEADY STATE -->

    <div class="heat-assumption">

      <svg viewBox="0 0 180 120" xmlns="http://www.w3.org/2000/svg">

        <path d="M25 30 H165 M25 50 H165
                 M25 70 H165 M25 90 H165
                 M45 15 V95 M65 15 V95
                 M85 15 V95 M105 15 V95
                 M125 15 V95 M145 15 V95
                 M165 15 V95"
              stroke="#64849b"
              stroke-opacity="0.12"
              fill="none"/>

        <path d="M25 12 V95 H168"
              stroke="#81909a" fill="none"/>

        <path d="M28 80 C42 80 42 35 68 35
                 H163 V95 H28 Z"
              fill="#64849b" fill-opacity="0.12"/>

        <path d="M28 80 C42 80 42 35 68 35 H163"
              stroke="#64849b"
              stroke-width="2.5" fill="none"/>

        <path d="M72 22 V87"
              stroke="#64849b"
              stroke-dasharray="3 3"/>

        <text x="118" y="27" text-anchor="middle"
              font-size="10" fill="#64849b">STEADY</text>

        <text x="12" y="18" font-size="11" fill="#888">X</text>
        <text x="165" y="108" font-size="11" fill="#888">t</text>

      </svg>

      <span class="heat-assumption-title">
        Steady State
      </span>

      <span class="heat-assumption-formula">
        ∂X/∂t = 0
      </span>

    </div>


    <!-- INCOMPRESSIBLE FLOW -->

    <div class="heat-assumption">

      <svg viewBox="0 0 180 120" xmlns="http://www.w3.org/2000/svg">

        <path d="M10 25 H55 L90 40 H170
                 V80 H90 L55 95 H10 Z"
              fill="#729b91" fill-opacity="0.12"
              stroke="#729b91" stroke-width="1.5"/>

        <g fill="#729b91" fill-opacity="0.8">

          <circle cx="20" cy="41" r="3"/>
          <circle cx="34" cy="41" r="3"/>
          <circle cx="48" cy="41" r="3"/>

          <circle cx="20" cy="79" r="3"/>
          <circle cx="34" cy="79" r="3"/>
          <circle cx="48" cy="79" r="3"/>

          <circle cx="64" cy="50" r="3"/>
          <circle cx="82" cy="50" r="3"/>
          <circle cx="100" cy="50" r="3"/>
          <circle cx="118" cy="50" r="3"/>
          <circle cx="136" cy="50" r="3"/>
          <circle cx="154" cy="50" r="3"/>

          <circle cx="64" cy="70" r="3"/>
          <circle cx="82" cy="70" r="3"/>
          <circle cx="100" cy="70" r="3"/>
          <circle cx="118" cy="70" r="3"/>
          <circle cx="136" cy="70" r="3"/>
          <circle cx="154" cy="70" r="3"/>

        </g>

        <path d="M18 60 H153
                 L145 54 M153 60 L145 66"
              stroke="#729b91"
              stroke-width="2" fill="none"/>

        <path d="M10 18 H55 M10 14 V22
                 M55 14 V22 M92 32 H170"
              stroke="#729b91"
              stroke-opacity="0.6"
              stroke-dasharray="3 2" fill="none"/>

        <text x="90" y="111" text-anchor="middle"
              font-size="11" fill="#729b91">ρ₁ = ρ₂</text>

      </svg>

      <span class="heat-assumption-title">
        Incompressible Flow
      </span>

      <span class="heat-assumption-formula">
        ρ = constant
      </span>

    </div>


    <!-- KINETIC AND POTENTIAL ENERGY -->

    <div class="heat-assumption">

      <svg viewBox="0 0 180 120" xmlns="http://www.w3.org/2000/svg">

        <path d="M15 95 H167"
              stroke="#999" stroke-dasharray="4 3"/>

        <path d="M30 95 V40 H150 V95"
              stroke="#b69b6a"
              stroke-dasharray="3 3" fill="none"/>

        <rect x="20" y="30" width="140" height="20"
              fill="#b69b6a" fill-opacity="0.12"
              stroke="#b69b6a"/>

        <path d="M27 40 H65 M58 35 L65 40 L58 45
                 M111 40 H149 M142 35 L149 40 L142 45"
              stroke="#b69b6a"
              stroke-width="2" fill="none"/>

        <path d="M30 55 V91
                 M25 60 L30 55 L35 60
                 M25 86 L30 91 L35 86
                 M150 55 V91
                 M145 60 L150 55 L155 60
                 M145 86 L150 91 L155 86"
              stroke="#b69b6a" fill="none"/>

        <g font-size="11" fill="#b69b6a">
          <text x="48" y="22">v₁</text>
          <text x="130" y="22">v₂</text>
          <text x="38" y="76">z₁</text>
          <text x="130" y="76">z₂</text>
        </g>

      </svg>

      <span class="heat-assumption-title">
        Negligible KE &amp; PE Changes
      </span>

      <span class="heat-assumption-formula">
        ΔKE ≈ ΔPE ≈ 0
      </span>

    </div>


    <!-- NO SHAFT WORK -->

    <div class="heat-assumption">

      <svg viewBox="0 0 180 120" xmlns="http://www.w3.org/2000/svg">

        <rect x="12" y="18" width="156" height="85" rx="5"
              stroke="#8b829e" stroke-dasharray="4 3"
              fill="#8b829e" fill-opacity="0.05"/>

        <path d="M20 60 H160"
              stroke="#8b829e"
              stroke-width="8" stroke-opacity="0.25"/>

        <g transform="translate(90 60)">

          <g fill="#8b829e">

            <rect x="-5" y="-36" width="10" height="13" rx="1"/>
            <rect x="-5" y="-36" width="10" height="13" rx="1" transform="rotate(30)"/>
            <rect x="-5" y="-36" width="10" height="13" rx="1" transform="rotate(60)"/>
            <rect x="-5" y="-36" width="10" height="13" rx="1" transform="rotate(90)"/>
            <rect x="-5" y="-36" width="10" height="13" rx="1" transform="rotate(120)"/>
            <rect x="-5" y="-36" width="10" height="13" rx="1" transform="rotate(150)"/>
            <rect x="-5" y="-36" width="10" height="13" rx="1" transform="rotate(180)"/>
            <rect x="-5" y="-36" width="10" height="13" rx="1" transform="rotate(210)"/>
            <rect x="-5" y="-36" width="10" height="13" rx="1" transform="rotate(240)"/>
            <rect x="-5" y="-36" width="10" height="13" rx="1" transform="rotate(270)"/>
            <rect x="-5" y="-36" width="10" height="13" rx="1" transform="rotate(300)"/>
            <rect x="-5" y="-36" width="10" height="13" rx="1" transform="rotate(330)"/>

          </g>

          <circle r="28" fill="#8b829e"
                  fill-opacity="0.2"
                  stroke="#8b829e" stroke-width="2"/>

          <circle r="18" fill="none"
                  stroke="#8b829e" stroke-opacity="0.6"/>

          <circle r="7" fill="#8b829e"
                  fill-opacity="0.5" stroke="#8b829e"/>

        </g>

        <path d="M45 105 L135 15"
              stroke="#c47c62" stroke-width="2.5"/>

      </svg>

      <span class="heat-assumption-title">
        No Shaft Work
      </span>

      <span class="heat-assumption-formula">
        Ẇ<sub>s</sub> = 0
      </span>

    </div>


    <!-- NEGLIGIBLE EXTERNAL HEAT LOSS -->

    <div class="heat-assumption">

      <svg viewBox="0 0 180 120" xmlns="http://www.w3.org/2000/svg">

        <rect x="25" y="14" width="130" height="90" rx="5"
              stroke="#c47c62" stroke-dasharray="4 3"
              fill="#c47c62" fill-opacity="0.05"/>

        <rect x="35" y="24" width="110" height="70" rx="3"
              stroke="#c47c62"
              fill="#c47c62" fill-opacity="0.09"/>

        <g stroke="#c47c62" stroke-opacity="0.65" fill="none">

          <path d="M44 29 l8 8 -8 8 8 8 -8 8 8 8 -8 8 8 8"/>
          <path d="M56 29 l8 8 -8 8 8 8 -8 8 8 8 -8 8 8 8"/>
          <path d="M68 29 l8 8 -8 8 8 8 -8 8 8 8 -8 8 8 8"/>
          <path d="M80 29 l8 8 -8 8 8 8 -8 8 8 8 -8 8 8 8"/>
          <path d="M92 29 l8 8 -8 8 8 8 -8 8 8 8 -8 8 8 8"/>
          <path d="M104 29 l8 8 -8 8 8 8 -8 8 8 8 -8 8 8 8"/>
          <path d="M116 29 l8 8 -8 8 8 8 -8 8 8 8 -8 8 8 8"/>
          <path d="M128 29 l8 8 -8 8 8 8 -8 8 8 8 -8 8 8 8"/>

        </g>

        <path d="M10 42 H35 M145 42 H170"
              stroke="#c47c62" stroke-width="5"/>

        <path d="M10 77 H35 M145 77 H170"
              stroke="#64849b" stroke-width="5"/>

        <path d="M90 14 V2 M84 7 L90 2 L96 7"
              stroke="#c47c62" fill="none"/>

        <path d="M82 3 L98 14 M98 3 L82 14"
              stroke="#c47c62" stroke-width="2"/>

        <text x="90" y="117" font-size="9"
              text-anchor="middle" fill="#c47c62">
          ADIABATIC BOUNDARY
        </text>

      </svg>

      <span class="heat-assumption-title">
        Negligible External Heat Loss
      </span>

      <span class="heat-assumption-formula">
        Q̇<sub>ext</sub> ≈ 0
      </span>

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
