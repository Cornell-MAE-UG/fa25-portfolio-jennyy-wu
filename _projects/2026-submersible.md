---
layout: project
title: Submersible XRP
permalink: /projects/submersible-xrp/
description: Cornell Cup Robotics — Underwater Robotics and Mechanical Design
technologies: [Fusion 360, CAD, 3D Printing, Rack-and-Pinion, Buoyancy, Waterproofing, Robotics]
---

<style>
/* ===== SUBMERSIBLE XRP PROJECT PAGE ===== */

.sub-page {
  width: 85vw;
  max-width: 900px;
  margin-left: 50%;
  transform: translateX(-50%);
  padding: 20px 0 80px;
  font-family: "Helvetica Neue", Arial, sans-serif;
  color: #222;
  text-align: center;
  box-sizing: border-box;
}

.sub-page * {
  box-sizing: border-box;
}

/* ===== TITLES AND TEXT ===== */

.sub-page .sub-main-title {
  font-family: Georgia, "Times New Roman", serif;
  font-size: clamp(44px, 5vw, 58px);
  font-weight: 700;
  letter-spacing: -0.045em;
  line-height: 1.1;
  margin: 0 auto 14px;
}

.sub-page h2 {
  font-family: Georgia, "Times New Roman", serif;
  font-size: clamp(29px, 3vw, 38px);
  font-weight: 400;
  letter-spacing: -0.035em;
  line-height: 1.25;
  color: #171717;
  margin: 0 0 18px;
}

.sub-page h3 {
  font-size: 21px;
  font-weight: 500;
  letter-spacing: -0.025em;
  margin: 24px 0 14px;
}

.sub-page p {
  font-size: 16px;
  line-height: 1.85;
  color: #444;
  margin: 0 0 14px;
}

.sub-page section {
  margin-bottom: 42px;
}

.sub-text {
  max-width: 800px;
  margin: 0 auto;
}

/* ===== PROJECT METADATA ===== */

.sub-page .sub-meta {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 25px;
  align-items: center;
  width: 100%;
  margin: 0 auto 20px;
  padding: 8px 0;
  border-top: 1px solid #e6e6e6;
  border-bottom: 1px solid #e6e6e6;
}

.sub-meta-heading {
  font-size: 11px;
  font-weight: 700;
  letter-spacing: 1.5px;
  text-transform: uppercase;
  color: #999;
  margin-bottom: 8px;
}

.sub-meta-value {
  font-size: 15px;
  line-height: 1.6;
  color: #333;
}

/* ===== IMAGES AND CAPTIONS ===== */

.sub-page figure {
  margin: 0;
  min-width: 0;
}

.sub-page img {
  display: block;
  width: 100%;
  height: auto;
  margin: 0 auto;
  border-radius: 4px;
}

.sub-page figcaption {
  font-size: 12px;
  line-height: 1.65;
  color: #888;
  margin-top: 8px;
}

.sub-page .sub-hero {
  width: 70%;
  max-width: 630px;
  margin: 22px auto;
}

.sub-page .sub-full {
  width: 100%;
  margin: 22px auto;
}

.sub-page .sub-gallery {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 24px;
  width: 100%;
  margin: 22px auto;
}

.sub-page .sub-gallery figure {
  width: 100%;
}

/* ===== PLACEHOLDERS ===== */

.sub-placeholder {
  width: 100%;
  aspect-ratio: 4 / 3;
  background: #f5f5f3;
  border: 1px dashed #d5d5d2;
  border-radius: 4px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 25px;
}

.sub-placeholder.wide {
  aspect-ratio: 16 / 9;
}

.sub-placeholder-icon {
  font-size: 27px;
  font-weight: 300;
  color: #aaa;
  margin-bottom: 13px;
}

.sub-placeholder-title {
  font-size: 14px;
  font-weight: 600;
  color: #777;
  margin-bottom: 8px;
}

.sub-placeholder-note {
  font-size: 12px;
  line-height: 1.6;
  color: #aaa;
  max-width: 330px;
}

/* ===== ENGINEERING CALLOUTS ===== */

.sub-specs {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 18px;
  margin: 18px 0 20px;
}

.sub-spec {
  background: #f7f7f6;
  padding: 25px 15px;
  border-radius: 4px;
}

.sub-spec-number {
  font-size: 31px;
  font-weight: 600;
  letter-spacing: -1px;
  margin-bottom: 7px;
}

.sub-spec-name {
  font-size: 12px;
  line-height: 1.5;
  color: #777;
}

.sub-equation {
  background: #f7f7f6;
  padding: 30px 20px;
  margin: 22px auto;
  border-radius: 4px;
}

.sub-equation-main {
  font-size: clamp(20px, 3vw, 29px);
  font-weight: 500;
  margin-bottom: 10px;
}

.sub-equation-note {
  font-size: 12px;
  color: #888;
  line-height: 1.7;
}

/* ===== MOBILE ===== */

@media (max-width: 700px) {
  .sub-page {
    width: calc(100% - 36px);
    padding: 20px 0 65px;
  }

  .sub-page section {
    margin-bottom: 35px;
  }

  .sub-page .sub-meta {
    gap: 10px;
  }

  .sub-meta-value {
    font-size: 13px;
  }

  .sub-page .sub-hero {
    width: 100%;
    max-width: 100%;
  }

  .sub-page .sub-gallery,
  .sub-specs {
    grid-template-columns: 1fr;
  }

  .sub-page p {
    font-size: 15px;
  }
}
</style>

<div class="sub-page">

  <!-- ===== MAIN TITLE ===== -->

  <h1 class="sub-main-title">Submersible XRP</h1>

  <!-- ===== PROJECT OVERVIEW ===== -->

  <section>

    <div class="sub-meta">
      <div>
        <div class="sub-meta-heading">Role</div>
        <div class="sub-meta-value">
          Mechanical Design &amp; Prototyping
        </div>
      </div>

      <div>
        <div class="sub-meta-heading">Year</div>
        <div class="sub-meta-value">2026–Present</div>
      </div>

      <div>
        <div class="sub-meta-heading">Team</div>
        <div class="sub-meta-value">
          Cornell Cup Robotics
        </div>
      </div>
    </div>

    <h2>Project Overview</h2>

    <div class="sub-text">
      <p>
        The Submersible XRP is a Cornell Cup Robotics
        project focused on developing an underwater
        robot capable of collecting water samples for
        microplastics research in collaboration with
        EarthEcho. The robot uses a waterproof housing,
        motor-driven thrusters, and a syringe-based
        ballast system to control its movement and depth.
      </p>

      <p>
        I worked on the mechanical design and prototyping
        of the robot, particularly its waterproof housing
        and syringe-based ballast mechanisms. My work
        involved designing components in Fusion 360,
        3D printing prototypes, assembling mechanisms,
        and troubleshooting issues related to
        waterproofing and buoyancy.
      </p>
    </div>

    <figure class="sub-hero">
      <img
        src="{{ '/assets/images/submersible.jpeg' | relative_url }}"
        alt="Submersible XRP underwater robotics project"
        loading="lazy"
      >
      <figcaption>
        Figure 1. Submersible XRP robotic system.
      </figcaption>
    </figure>

  </section>

  <!-- ===== SYSTEM DESIGN ===== -->

  <section>

    <h2>System Design &amp; CAD Assembly</h2>

    <div class="sub-text">
      <p>
        The robot was designed around a cylindrical
        waterproof enclosure containing the electronics,
        motors, and syringe mechanisms. Two external
        thrusters provide underwater movement, while
        three syringes serve separate functions: two
        control buoyancy and one collects water samples.
      </p>

      <p>
        I used Fusion 360 to design the housing and
        internal mounting components, considering
        how the electronics, XRP platform, motors,
        and moving mechanisms would fit together.
        A major challenge was keeping the assembly
        compact without sacrificing access to
        components or compromising the waterproof seal.
      </p>
    </div>

    <div class="sub-specs">
      <div class="sub-spec">
        <div class="sub-spec-number">2</div>
        <div class="sub-spec-name">Propulsion thrusters</div>
      </div>

      <div class="sub-spec">
        <div class="sub-spec-number">2</div>
        <div class="sub-spec-name">Ballast syringes</div>
      </div>

      <div class="sub-spec">
        <div class="sub-spec-number">1</div>
        <div class="sub-spec-name">Water sampling syringe</div>
      </div>
    </div>

    <div class="sub-gallery">

      <figure>
        <div class="sub-placeholder">
          <div class="sub-placeholder-icon">+</div>
          <div class="sub-placeholder-title">
            Full CAD Assembly
          </div>
          <div class="sub-placeholder-note">
            Fusion 360 isometric view of the
            complete submersible.
          </div>
        </div>
        <figcaption>
          Figure 2. CAD model of the complete robot.
        </figcaption>
      </figure>

      <figure>
        <div class="sub-placeholder">
          <div class="sub-placeholder-icon">+</div>
          <div class="sub-placeholder-title">
            Internal Component Layout
          </div>
          <div class="sub-placeholder-note">
            CAD view showing the electronics,
            syringes, motors, and mounting trays.
          </div>
        </div>
        <figcaption>
          Figure 3. Internal mechanical assembly.
        </figcaption>
      </figure>

    </div>

  </section>

  <!-- ===== BALLAST SYSTEM ===== -->

  <section>

    <h2>Syringe-Based Ballast System</h2>

    <div class="sub-text">
      <p>
        To control the robot's buoyancy, we developed
        a ballast system using two syringes driven
        by N20 motors and rack-and-pinion mechanisms.
        The motor rotates a pinion gear, which drives
        a linear rack connected to the syringe plunger.
        This converts the motor's rotational motion
        into the linear motion needed to draw in
        or expel water.
      </p>

      <p>
        Retracting the plunger draws water into the
        syringe, increasing the robot's mass and
        helping it sink. Extending the plunger
        expels water, decreasing its mass and
        allowing the robot to rise. This provides
        a way to adjust buoyancy without relying
        entirely on the thrusters.
      </p>

      <p>
        The design required considering motor torque,
        rack-and-pinion alignment, syringe friction,
        available water volume, and the placement
        of both ballast mechanisms inside the housing.
        We tested the mechanism separately to verify
        that the motors could move the plungers.
      </p>
    </div>


    <div class="iss-gallery">

      <figure class="iss-hero">
      <img
        src="{{ '/assets/images/motor_mount.jpeg' | relative_url }}"
        alt="Close-up of the motor, pinion rack, and syringe plunger."
        loading="lazy"
      >
      <figcaption>
        Figure 4. CAD model of the syringe actuation mechanism.
      </figcaption>
    </figure>
        <figure class="iss-hero">
      <img
        src="{{ '/assets/images/sub_ballast.jpeg' | relative_url }}"
        alt="Assembled motor-driven syringe mechanism"
        loading="lazy"
      >
      <figcaption>
        Figure 5. Physical prototype of the ballast system.
      </figcaption>
    </figure>

    </div>

  </section>

  <!-- ===== BUOYANCY ===== -->

  <section>

    <h2>Buoyancy &amp; Housing Optimization</h2>

    <div class="sub-text">
      <p>
        One of the biggest engineering challenges was
        that our original housing was too buoyant.
        Because the enclosure displaced a relatively
        large volume of water, the upward buoyant
        force exceeded the robot's weight, even
        when the ballast syringes were filled.
      </p>

      <p>
        According to Archimedes' principle, the
        buoyant force depends on the volume of
        water displaced by the robot:
      </p>
    </div>

    <div class="sub-equation">
      <div class="sub-equation-main">
        F<sub>b</sub> = ρ<sub>water</sub> × g × V<sub>displaced</sub>
      </div>
      <div class="sub-equation-note">
        Buoyant force = water density × gravitational acceleration
        × displaced volume
      </div>
    </div>

    <div class="sub-text">
      <p>
        A larger housing displaces more water and
        therefore experiences a greater upward
        buoyant force. To address this, we began
        redesigning the enclosure with a smaller
        overall volume while preserving enough
        internal space for the electronics, motors,
        and syringe mechanisms.
      </p>

      <p>
        This required balancing the packaging of
        internal components with the amount of
        water the ballast system could take in.
        The goal is to reduce the robot's excess
        buoyancy so the syringes can effectively
        control its depth.
      </p>
    </div>

    <div class="sub-gallery">

      <figure>
        <div class="sub-placeholder">
          <div class="sub-placeholder-icon">+</div>
          <div class="sub-placeholder-title">
            Original Housing
          </div>
          <div class="sub-placeholder-note">
            CAD view showing the initial
            cylindrical enclosure.
          </div>
        </div>
        <figcaption>
          Figure 6. Original housing geometry.
        </figcaption>
      </figure>

      <figure>
        <div class="sub-placeholder">
          <div class="sub-placeholder-icon">+</div>
          <div class="sub-placeholder-title">
            Reduced-Volume Housing
          </div>
          <div class="sub-placeholder-note">
            Updated CAD design showing the
            more compact enclosure.
          </div>
        </div>
        <figcaption>
          Figure 7. Housing redesign to reduce displaced volume.
        </figcaption>
      </figure>

    </div>

  </section>

  <!-- ===== WATERPROOFING ===== -->

  <section>

    <h2>Waterproof Housing Design</h2>

    <div class="sub-text">
      <p>
        Waterproofing was another major challenge
        because even a small leak could damage
        the electronics inside the robot. Our
        original design used a cylindrical tube
        with end caps containing openings for
        external connections.
      </p>

      <p>
        During manufacturing, we drilled the
        port holes before fully tightening the
        end caps. When the caps were installed
        in their final positions, the holes no
        longer aligned correctly.
      </p>

      <p>
        We attempted to correct the problem
        by redrilling the openings and applying
        sealing material, but the repairs did
        not produce a reliable watertight seal.
      </p>
    </div>

    <h3>Housing Redesign</h3>

    <div class="sub-text">
      <p>
        Rather than continuing to repair the
        original end caps, we began redesigning
        the housing to incorporate the port
        openings directly into the 3D-printed
        components. This approach aims to
        improve alignment, reduce potential
        leak paths, and make assembly more
        consistent.
      </p>

      <p>
        The redesign also considers sealing
        around external connections, access
        to internal components, and reducing
        the overall housing volume to address
        the buoyancy problem.
      </p>
    </div>

    <div class="sub-gallery">

      <figure>
        <div class="sub-placeholder">
          <div class="sub-placeholder-icon">+</div>
          <div class="sub-placeholder-title">
            Original End Cap
          </div>
          <div class="sub-placeholder-note">
            Photo or CAD view showing the
            drilled ports and alignment issue.
          </div>
        </div>
        <figcaption>
          Figure 8. Original end-cap design.
        </figcaption>
      </figure>

      <figure>
        <div class="sub-placeholder">
          <div class="sub-placeholder-icon">+</div>
          <div class="sub-placeholder-title">
            Redesigned End Cap
          </div>
          <div class="sub-placeholder-note">
            CAD view of the updated port
            geometry and sealing features.
          </div>
        </div>
        <figcaption>
          Figure 9. Redesigned end cap with integrated ports.
        </figcaption>
      </figure>

    </div>

  </section>

  <!-- ===== PROTOTYPING ===== -->

  <section>

    <h2>3D Printing &amp; Prototyping</h2>

    <div class="sub-text">
      <p>
        I used Fusion 360 and 3D printing to
        develop and revise the housing, mounting
        trays, and mechanical components.
        Prototyping allowed us to identify
        problems with fit, port placement,
        component clearance, and assembly
        before integrating the full robot.
      </p>

      <p>
        Design considerations included the
        fit between the tube and end caps,
        motor and syringe mounting positions,
        clearance for moving racks, and
        space for electronics and wiring.
        These iterations helped us improve
        the mechanical layout as the
        design evolved.
      </p>
    </div>

    <div class="sub-gallery">

      <figure>
        <div class="sub-placeholder">
          <div class="sub-placeholder-icon">+</div>
          <div class="sub-placeholder-title">
            3D-Printed Components
          </div>
          <div class="sub-placeholder-note">
            Photograph of printed housing,
            mounting, or syringe components.
          </div>
        </div>
        <figcaption>
          Figure 10. Manufactured prototype components.
        </figcaption>
      </figure>

      <figure>
        <div class="sub-placeholder">
          <div class="sub-placeholder-icon">+</div>
          <div class="sub-placeholder-title">
            Internal Assembly
          </div>
          <div class="sub-placeholder-note">
            Photograph showing the mechanical
            components installed inside the housing.
          </div>
        </div>
        <figcaption>
          Figure 11. Submersible mechanical assembly.
        </figcaption>
      </figure>

    </div>

  </section>

  <!-- ===== TESTING ===== -->

  <section>

    <h2>Testing &amp; Results</h2>

    <div class="sub-text">
      <p>
        We tested the thrusters and ballast
        system individually to verify that
        the mechanisms operated as intended.
        Both systems were able to move
        during initial testing.
      </p>

      <p>
        However, the housing introduced
        separate challenges involving
        waterproofing and buoyancy.
        These tests helped us identify
        the areas requiring redesign
        before integrating the electronics
        into a fully operational underwater robot.
      </p>
    </div>

    <h3>Waterproofing Tests</h3>

    <div class="sub-text">
      <p>
        Our leak-testing approach involves
        assembling the empty housing without
        electronics, submerging it in water,
        and introducing low-pressure air.
        Escaping bubbles can help identify
        gaps around ports, end caps, or
        other sealing surfaces.
      </p>

      <p>
        This allows us to investigate
        potential leak paths without
        exposing the electronics to water.
      </p>
    </div>

    <div class="sub-gallery">

      <figure>
        <div class="sub-placeholder">
          <div class="sub-placeholder-icon">+</div>
          <div class="sub-placeholder-title">
            Waterproofing Test
          </div>
          <div class="sub-placeholder-note">
            Photo of the empty housing
            during submerged leak testing.
          </div>
        </div>
        <figcaption>
          Figure 12. Housing leak-testing setup.
        </figcaption>
      </figure>

      <figure>
        <div class="sub-placeholder">
          <div class="sub-placeholder-icon">+</div>
          <div class="sub-placeholder-title">
            Ballast Mechanism Test
          </div>
          <div class="sub-placeholder-note">
            Photo of the syringe and
            rack-and-pinion test setup.
          </div>
        </div>
        <figcaption>
          Figure 13. Testing the syringe actuation system.
        </figcaption>
      </figure>

    </div>

    <h3>Current Design Status</h3>

    <div class="sub-text">
      <p>
        The initial thruster and syringe
        actuation tests demonstrated that
        the individual mechanisms could move
        as intended. The housing redesign
        is focused on improving waterproofing
        and reducing displaced volume.
        Further testing is needed to verify
        the revised enclosure and demonstrate
        reliable buoyancy control underwater.
      </p>
    </div>

    <figure class="sub-full">
      <div class="sub-placeholder wide">
        <div class="sub-placeholder-icon">▶</div>
        <div class="sub-placeholder-title">
          Submersible Testing Video
        </div>
        <div class="sub-placeholder-note">
          Add footage of the thrusters,
          syringe actuation, or underwater testing.
        </div>
      </div>
      <figcaption>
        Video 1. Submersible XRP mechanical testing.
      </figcaption>
    </figure>

  </section>

</div>