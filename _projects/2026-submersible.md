---
layout: project
title: Submersible
permalink: /projects/submersible-xrp/
description: Cornell Cup Robotics — Underwater Robotics and Mechanical Design
technologies: [Fusion 360, CAD, 3D Printing, Rack-and-Pinion, Buoyancy, Waterproofing, Robotics, MATLAB, System Dynamics, Feedback Control]
---

<style>
/* ===== PAGE LAYOUT ===== */

.sub-page {
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

.sub-page * {
  box-sizing: border-box;
}

.sub-page .sub-main-title {
  font-family: Georgia, "Times New Roman", serif;
  font-size: clamp(42px, 5vw, 56px);
  font-weight: 700;
  letter-spacing: -0.045em;
  margin: 0 0 16px;
}

.sub-page h2 {
  font-family: Georgia, "Times New Roman", serif;
  font-size: clamp(29px, 3vw, 38px);
  font-weight: 400;
  letter-spacing: -0.035em;
  line-height: 1.25;
  margin: 0 0 18px;
}

.sub-page h3 {
  font-size: 20px;
  font-weight: 500;
  margin: 26px 0 14px;
}

.sub-page p {
  font-size: 16px;
  line-height: 1.85;
  color: #444;
  margin: 0 0 14px;
}

.sub-page section {
  margin-bottom: 48px;
}

.sub-text {
  max-width: 800px;
  margin: 0 auto;
}

/* ===== PROJECT METADATA ===== */

.sub-meta {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 20px;
  padding: 20px 0;
  margin: 0 auto 30px;
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
  font-size: 14px;
  line-height: 1.6;
  color: #333;
}

/* ===== IMAGES ===== */

.sub-page figure {
  margin: 0;
  min-width: 0;
}

.sub-page img {
  display: block;
  width: 100%;
  height: auto;
  border-radius: 4px;
}

.sub-page figcaption {
  font-size: 12px;
  line-height: 1.65;
  color: #888;
  margin-top: 9px;
}

.sub-hero {
  width: 70%;
  max-width: 630px;
  margin: 24px auto !important;
}

.sub-gallery {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 24px;
  max-width: 800px;
  margin: 24px auto;
  align-items: start;
}

.sub-gallery figure {
  width: 100%;
}

.sub-gallery img {
  height: 280px;
  object-fit: contain;
}

.sub-full {
  max-width: 800px;
  margin: 24px auto !important;
}

/* ===== BALLAST PHOTOS ===== */

.sub-ballast-gallery {
  max-width: 800px;
  gap: 22px;
}

.sub-ballast-gallery img {
  width: 100%;
  height: 300px;
  object-fit: contain;
  background: #f7f7f6;
}

/* ===== IMAGE PLACEHOLDERS ===== */

.sub-placeholder {
  width: 100%;
  aspect-ratio: 4 / 3;
  background: #f5f5f3;
  border: 1px dashed #d5d5d2;
  border-radius: 4px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 25px;
  text-align: center;
}

.sub-placeholder.wide {
  aspect-ratio: 16 / 9;
}

.sub-placeholder-icon {
  font-size: 27px;
  font-weight: 300;
  color: #aaa;
  margin-bottom: 12px;
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
  max-width: 300px;
}

/* ===== ENGINEERING DETAILS ===== */

.sub-specs {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 18px;
  margin: 24px auto;
}

.sub-spec {
  background: #f7f7f6;
  padding: 24px 15px;
  border-radius: 4px;
}

.sub-spec-number {
  font-size: 30px;
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
  max-width: 800px;
  background: #f7f7f6;
  padding: 28px 20px;
  margin: 24px auto;
  border-radius: 4px;
}

.sub-equation-main {
  font-size: clamp(20px, 3vw, 29px);
  font-weight: 500;
  margin-bottom: 10px;
}

.sub-equation-note {
  font-size: 12px;
  line-height: 1.7;
  color: #888;
}

.sub-project-note {
  font-size: 12px !important;
  color: #888 !important;
  letter-spacing: 0.02em;
}

/* ===== ALIGN SHARED PAGE FOOTER ===== */

.page-content > .wrapper,
.page-content > .container,
main.page-content > .wrapper {
  width: 85vw !important;
  max-width: 900px !important;
  box-sizing: border-box;
}

/* ===== MOBILE ===== */

@media (max-width: 700px) {
  .sub-page {
    width: calc(100% - 36px);
    padding: 20px 0 60px;
  }

  .sub-page section {
    margin-bottom: 38px;
  }

  .sub-meta {
    gap: 10px;
  }

  .sub-meta-value {
    font-size: 13px;
  }

  .sub-hero {
    width: 100%;
  }

  .sub-gallery,
  .sub-specs {
    grid-template-columns: 1fr;
  }

  .sub-gallery img,
  .sub-ballast-gallery img {
    height: auto;
    max-height: 360px;
  }

  .sub-page p {
    font-size: 15px;
  }

  .page-content > .wrapper,
  .page-content > .container,
  main.page-content > .wrapper {
    width: calc(100% - 36px) !important;
  }
}
</style>

<div class="sub-page">

  <!-- ===== TITLE ===== -->

  <h1 class="sub-main-title">Submersible</h1>

  <!-- ===== PROJECT OVERVIEW ===== -->

  <section id="overview">

    <div class="sub-meta">

      <div>
        <div class="sub-meta-heading">Role</div>
        <div class="sub-meta-value">
          MechE
        </div>
      </div>

      <div>
        <div class="sub-meta-heading">Year</div>
        <div class="sub-meta-value">
          2026–Present
        </div>
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
        The Submersible is a Cornell Cup Robotics
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
        alt="Submersible underwater robotics project"
      >
      <figcaption>
        Figure 1. Submersible robotic system.
      </figcaption>
    </figure>

  </section>

  <!-- ===== SYSTEM DESIGN ===== -->

  <section id="system-design">

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
            Add a Fusion 360 isometric view
            of the complete submersible.
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
            Add a CAD view of the electronics,
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

  <section id="ballast">

    <h2>Syringe-Based Ballast System</h2>

    <div class="sub-text">
      <p>
        To control the robot's buoyancy, we developed
        a ballast system using two syringes driven
        by N20 motors and rack-and-pinion mechanisms.
        The motor rotates a pinion gear, which drives
        a linear rack connected to the syringe plunger.
        This converts rotational motion into the
        linear motion needed to draw in or expel water.
      </p>

      <p>
        Retracting the plunger draws water into the
        syringe, increasing the robot's mass and
        helping it sink. Extending the plunger expels
        water, decreasing its mass and allowing the
        robot to rise. This provides a way to adjust
        buoyancy without relying entirely on the thrusters.
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

    <div class="sub-gallery sub-ballast-gallery">

      <figure>
        <img
          src="{{ '/assets/images/motor_mount.jpeg' | relative_url }}"
          alt="Motor mounting and syringe actuation prototype"
          loading="lazy"
        >
        <figcaption>
          Figure 4. 3D-printed motor mounting and
          syringe actuation components.
        </figcaption>
      </figure>

      <figure>
        <img
          src="{{ '/assets/images/sub_ballast.jpeg' | relative_url }}"
          alt="Physical rack-and-pinion ballast prototype"
          loading="lazy"
        >
        <figcaption>
          Figure 5. Physical prototype of the
          rack-and-pinion ballast system.
        </figcaption>
      </figure>

    </div>

  </section>

  <!-- ===== BUOYANCY ===== -->

  <section id="buoyancy">

    <h2>Buoyancy &amp; Housing Optimization</h2>

    <div class="sub-text">
      <p>
        One of the biggest engineering challenges
        was that our original housing was too buoyant.
        Because the enclosure displaced a relatively
        large volume of water, the upward buoyant
        force exceeded the robot's weight, even
        when the ballast syringes were filled.
      </p>

      <p>
        According to Archimedes' principle,
        the buoyant force depends on the volume
        of water displaced by the robot:
      </p>
    </div>

    <div class="sub-equation">
      <div class="sub-equation-main">
        F<sub>b</sub> =
        ρ<sub>water</sub> × g × V<sub>displaced</sub>
      </div>
      <div class="sub-equation-note">
        Buoyant force = water density × gravitational
        acceleration × displaced volume
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
        The goal is to reduce excess buoyancy
        so the syringes can effectively
        control the robot's depth.
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
            Add CAD view of the initial
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
            Add updated CAD design showing
            the more compact enclosure.
          </div>
        </div>
        <figcaption>
          Figure 7. Housing redesign to reduce
          displaced volume.
        </figcaption>
      </figure>

    </div>

  </section>

  <!-- ===== WATERPROOFING ===== -->

  <section id="waterproofing">

    <h2>Waterproof Housing Design</h2>

    <div class="sub-text">
      <p>
        Waterproofing was another major challenge
        because even a small leak could damage
        the electronics inside the robot.
        Our original design used a cylindrical
        tube with end caps containing openings
        for external connections.
      </p>

      <p>
        During manufacturing, we drilled the
        port holes before fully tightening the
        end caps. When the caps were installed
        in their final positions, the holes
        no longer aligned correctly.
      </p>

      <p>
        We attempted to correct the problem
        by redrilling the openings and applying
        sealing material, but these repairs
        did not produce a reliable watertight seal.
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
        leak paths, and make assembly
        more consistent.
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
            Add photo or CAD view showing
            the drilled ports and alignment issue.
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
            Add CAD view of the updated
            port geometry and sealing features.
          </div>
        </div>
        <figcaption>
          Figure 9. Redesigned end cap
          with integrated ports.
        </figcaption>
      </figure>

    </div>

  </section>

  <!-- ===== PROTOTYPING ===== -->

  <section id="prototyping">

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
            Add photograph of printed housing,
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
            Add photograph showing components
            installed inside the housing.
          </div>
        </div>
        <figcaption>
          Figure 11. Submersible mechanical assembly.
        </figcaption>
      </figure>

    </div>

  </section>

  <!-- ===== SYSTEM DYNAMICS ===== -->

  <section id="system-dynamics">

    <h2>System Dynamics &amp; Control Modeling</h2>

    <p class="sub-project-note">
      MAE 3260 System Dynamics — Super Sub Bros.
    </p>

    <div class="sub-text">
      <p>
        Alongside the mechanical development of
        the Submersible, I began studying
        the robot's motion as part of MAE 3260:
        System Dynamics. Our project, "Super Sub Bros.,"
        investigates how two side-by-side thrusters
        produce forward motion and allow the robot
        to change its heading underwater.
      </p>

      <p>
        My role focuses on developing mathematical
        models using Newton's laws and differential
        equations, then deriving transfer functions
        relating thruster inputs to the robot's motion.
        We plan to use MATLAB to simulate the
        robot's open-loop response and study how
        different thrust inputs affect its movement.
      </p>
    </div>

    <h3>Dual-Thruster Motion Model</h3>

    <div class="sub-text">
      <p>
        When both thrusters generate equal thrust,
        their forces combine to move the robot
        forward. When the thrust differs between
        the two sides, the resulting moment causes
        the robot to turn. Our model will describe
        both forward and rotational motion.
      </p>
    </div>

    <div class="sub-gallery">

      <figure>
        <div class="sub-placeholder">
          <div class="sub-placeholder-icon">+</div>
          <div class="sub-placeholder-title">
            Equations of Motion
          </div>
          <div class="sub-placeholder-note">
            Add free-body diagram showing
            both thruster forces, geometry,
            and yaw moment.
          </div>
        </div>
        <figcaption>
          Figure 12. Dual-thruster free-body diagram.
        </figcaption>
      </figure>

      <figure>
        <div class="sub-placeholder">
          <div class="sub-placeholder-icon">+</div>
          <div class="sub-placeholder-title">
            MATLAB Open-Loop Response
          </div>
          <div class="sub-placeholder-note">
            Add MATLAB heading response
            plot for a selected thrust input.
          </div>
        </div>
        <figcaption>
          Figure 13. Open-loop heading simulation.
        </figcaption>
      </figure>

    </div>

    <h3>Feedback Control &amp; 90° Turn</h3>

    <div class="sub-text">
      <p>
        The next stage is to investigate feedback
        control for a commanded 90° turn.
        Using the mathematical model, we plan
        to design a controller and compare
        open-loop and closed-loop responses.
        We will evaluate turning accuracy,
        response time, and the robot's ability
        to reach the desired heading.
      </p>

      <p>
        This analysis connects our mechanical
        design decisions with the robot's
        dynamic behavior, providing a better
        understanding of how thruster inputs
        affect underwater movement.
      </p>
    </div>

    <div class="sub-gallery">

      <figure>
        <div class="sub-placeholder">
          <div class="sub-placeholder-icon">+</div>
          <div class="sub-placeholder-title">
            Feedback-Control Diagram
          </div>
          <div class="sub-placeholder-note">
            Add controller, robot dynamics,
            heading output, and feedback loop.
          </div>
        </div>
        <figcaption>
          Figure 14. Closed-loop control block diagram.
        </figcaption>
      </figure>

      <figure>
        <div class="sub-placeholder">
          <div class="sub-placeholder-icon">+</div>
          <div class="sub-placeholder-title">
            Open-Loop vs. Closed-Loop
          </div>
          <div class="sub-placeholder-note">
            Add MATLAB comparison of heading
            responses for a commanded 90° turn.
          </div>
        </div>
        <figcaption>
          Figure 15. Planned heading-response comparison.
        </figcaption>
      </figure>

    </div>

  </section>

  <!-- ===== TESTING ===== -->

  <section id="testing">

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
            Add photo of the empty housing
            during submerged leak testing.
          </div>
        </div>
        <figcaption>
          Figure 16. Housing leak-testing setup.
        </figcaption>
      </figure>

      <figure>
        <div class="sub-placeholder">
          <div class="sub-placeholder-icon">+</div>
          <div class="sub-placeholder-title">
            Ballast Mechanism Test
          </div>
          <div class="sub-placeholder-note">
            Add photo of the syringe and
            rack-and-pinion test setup.
          </div>
        </div>
        <figcaption>
          Figure 17. Testing the syringe actuation system.
        </figcaption>
      </figure>

    </div>

    <h3>Current Design Status</h3>

    <div class="sub-text">
      <p>
        Initial thruster and syringe actuation
        tests demonstrated that the individual
        mechanisms could move as intended.
        The housing redesign is focused on
        improving waterproofing and reducing
        displaced volume. Further testing
        is needed to verify the revised
        enclosure and demonstrate reliable
        buoyancy control underwater.
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
        Video 1. Submersible mechanical testing.
      </figcaption>
    </figure>

  </section>

</div>