---
layout: project
title: Fluid-Mechanical Dissection
permalink: /projects/fluid-mechanical-dissection/
description: MAE 3230 Fluid Mechanics — Rotary-Vane Vacuum Pump
technologies: [Fluid Mechanics, Mechanical Dissection, Vacuum Systems, Engineering Analysis]
---

<style>
/* ===== FLUID-MECHANICAL DISSECTION ===== */

.fluid-page {
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

.fluid-page * {
  box-sizing: border-box;
}

.fluid-page h1,
.fluid-page h2 {
  font-family: Georgia, "Times New Roman", serif;
  color: #171717;
  letter-spacing: -0.04em;
}

.fluid-page h1 {
  font-size: clamp(42px, 5vw, 58px);
  line-height: 1.1;
  margin: 0 0 16px;
}

.fluid-page h2 {
  font-size: clamp(30px, 3.5vw, 39px);
  font-weight: 400;
  margin: 0 0 18px;
}

.fluid-page p {
  max-width: 800px;
  margin: 0 auto 16px;
  font-size: 16px;
  line-height: 1.85;
  color: #444;
}

.fluid-page section {
  margin-bottom: 48px;
}

/* ===== PROJECT METADATA ===== */

.fluid-meta {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  padding: 18px 0;
  margin: 24px 0 28px;
  border-top: 1px solid #e5e5e5;
  border-bottom: 1px solid #e5e5e5;
}

.fluid-meta-label {
  display: block;
  font-size: 11px;
  font-weight: 700;
  letter-spacing: 1.5px;
  text-transform: uppercase;
  color: #999;
  margin-bottom: 5px;
}

.fluid-meta-value {
  font-size: 14px;
  color: #333;
}

/* ===== IMAGES ===== */

.fluid-page figure {
  margin: 24px auto;
}

.fluid-page img {
  display: block;
  width: 100%;
  height: auto;
  border-radius: 5px;
}

.fluid-hero {
  max-width: 650px;
}

.fluid-gallery {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 22px;
  max-width: 800px;
  margin: 24px auto;
}

.fluid-gallery figure {
  margin: 0;
}

.fluid-page figcaption {
  margin-top: 9px;
  font-size: 12px;
  line-height: 1.6;
  color: #888;
}

/* ===== IMAGE PLACEHOLDERS ===== */

.fluid-placeholder {
  min-height: 240px;
  padding: 25px;
  background: #f5f5f3;
  border: 1px dashed #d8d8d5;
  border-radius: 5px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #999;
  font-size: 13px;
}

/* ===== PROCESS ===== */

.fluid-process {
  max-width: 800px;
  margin: 24px auto;
  text-align: left;
}

.fluid-process-item {
  display: grid;
  grid-template-columns: 42px 1fr;
  gap: 15px;
  padding: 18px 0;
  border-bottom: 1px solid #e7e7e7;
}

.fluid-process-number {
  font-size: 13px;
  font-weight: 700;
  color: #888;
}

.fluid-process-item strong {
  display: block;
  font-size: 16px;
  margin-bottom: 5px;
}

.fluid-process-item p {
  margin: 0;
  font-size: 15px;
  line-height: 1.7;
}

/* ===== MOBILE ===== */

@media (max-width: 700px) {
  .fluid-page {
    width: calc(100% - 36px);
  }

  .fluid-meta {
    gap: 10px;
  }

  .fluid-meta-value {
    font-size: 12px;
  }

  .fluid-gallery {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="fluid-page">

  <!-- ===== INTRODUCTION ===== -->

  <section>
    <h1>Fluid-Mechanical Dissection</h1>

    <div class="fluid-meta">
      <div>
        <span class="fluid-meta-label">Course</span>
        <span class="fluid-meta-value">MAE 3230</span>
      </div>

      <div>
        <span class="fluid-meta-label">Focus</span>
        <span class="fluid-meta-value">Fluid Mechanics</span>
      </div>

      <div>
        <span class="fluid-meta-label">System</span>
        <span class="fluid-meta-value">Rotary-Vane Vacuum Pump</span>
      </div>
    </div>

    <p>
      For our MAE 3230 Fluid Mechanics project, my group is disassembling a rotary-vane vacuum pump to understand how its internal components work
      together to create suction.
    </p>

    <figure class="fluid-hero">
      <img
        src="{{ '/assets/images/vacuum_pump.JPG' | relative_url }}"
        alt="Rotary-vane vacuum pump"
      >
      <figcaption>
        Figure 1. Rotary-vane vacuum pump selected
        for mechanical dissection.
      </figcaption>
    </figure>
  </section>

  <!-- ===== HOW IT WORKS ===== -->

  <section>
    <h2>How a Rotary-Vane Pump Works</h2>

    <p>
      A rotary-vane vacuum pump uses a rotating,
      off-center rotor with sliding vanes to move
      air through a sealed chamber.
    </p>

    <p>
      As the rotor turns, the spaces between the
      vanes expand near the inlet, drawing air
      into the pump. These spaces then decrease
      in volume, compressing the trapped air
      and directing it toward the outlet.
    </p>

    <p>
      By continuously removing air from a connected
      system, the pump reduces its internal pressure
      and creates a vacuum.
    </p>
  </section>

  <!-- ===== DISSECTION ===== -->

  <section>
    <h2>Mechanical Dissection</h2>

    <p>
      Our goal is to examine the pump's internal
      construction and connect what we observe
      to the fluid mechanics behind its operation.
    </p>

    <div class="fluid-process">

      <div class="fluid-process-item">
        <span class="fluid-process-number">01</span>
        <div>
          <strong>Disassemble the Housing</strong>
          <p>
            Open the pump and document how its
            components are arranged.
          </p>
        </div>
      </div>

      <div class="fluid-process-item">
        <span class="fluid-process-number">02</span>
        <div>
          <strong>Identify the Internal Mechanisms</strong>
          <p>
            Examine the rotor, vanes, chamber,
            inlet, and outlet.
          </p>
        </div>
      </div>

      <div class="fluid-process-item">
        <span class="fluid-process-number">03</span>
        <div>
          <strong>Analyze the Fluid Motion</strong>
          <p>
            Investigate how changing chamber
            volume produces airflow and
            pressure differences.
          </p>
        </div>
      </div>

      <div class="fluid-process-item">
        <span class="fluid-process-number">04</span>
        <div>
          <strong>Connect Theory to Design</strong>
          <p>
            Consider how clearances, sealing,
            and component geometry influence
            pump performance.
          </p>
        </div>
      </div>

    </div>

    <div class="fluid-gallery">
      <figure>
        <div class="fluid-placeholder">
          Add disassembly photograph
        </div>
        <figcaption>
          Figure 2. Pump housing and internal assembly.
        </figcaption>
      </figure>

      <figure>
        <div class="fluid-placeholder">
          Add internal mechanism photograph
        </div>
        <figcaption>
          Figure 3. Rotor and vane mechanism.
        </figcaption>
      </figure>
    </div>
  </section>

  <!-- ===== ENGINEERING ANALYSIS ===== -->

  <section>
    <h2>Engineering Analysis</h2>

    <p>
      One of the main questions we're exploring
      is how the pump converts rotational motion
      into a pressure difference.
    </p>

    <p>
      We're looking at how the geometry of the
      rotor and chamber affects the volume
      of trapped air, and how sealing and
      mechanical clearances influence the
      pump's ability to maintain a vacuum.
    </p>
  </section>

  <!-- ===== PROJECT STATUS ===== -->

  <section>
    <h2>Next Steps</h2>

    <p>
      As we continue the dissection, we'll document
      the internal components, examine the pump's
      operating mechanism, and connect our
      observations to concepts from MAE 3230.
    </p>
  </section>

</div>
