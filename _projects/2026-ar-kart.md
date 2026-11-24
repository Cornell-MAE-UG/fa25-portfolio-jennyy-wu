---
layout: project
title: AR Kart
permalink: /projects/ar-kart/
description: Cornell Cup Robotics — Mechanical Design, Steering, and Prototyping
technologies: [Fusion 360, CAD, 3D Printing, Ackermann Steering, Drivetrain, Robotics]
---

<style>
/* ===== AR KART PROJECT PAGE ===== */

.kart-page {
  width: 85vw;
  max-width: 900px;
  margin-left: 50%;
  transform: translateX(-50%);
  padding: 20px 0 45px;
  font-family: "Helvetica Neue", Arial, sans-serif;
  color: #222;
  text-align: center;
  box-sizing: border-box;
}

.kart-page * {
  box-sizing: border-box;
}

/* ===== TYPOGRAPHY ===== */

.kart-page .kart-title {
  font-family: Georgia, "Times New Roman", serif;
  font-size: clamp(42px, 5vw, 56px);
  font-weight: 700;
  letter-spacing: -0.045em;
  line-height: 1.12;
  margin: 0 0 16px;
  color: #171717;
}

.kart-page h2 {
  font-family: Georgia, "Times New Roman", serif;
  font-size: clamp(29px, 3vw, 38px);
  font-weight: 400;
  letter-spacing: -0.035em;
  line-height: 1.25;
  margin: 0 0 18px;
  color: #171717;
}

.kart-page h3 {
  font-size: 20px;
  font-weight: 500;
  margin: 24px 0 14px;
}

.kart-page p {
  font-size: 16px;
  line-height: 1.85;
  color: #444;
  margin: 0 0 14px;
}

.kart-page section {
  margin-bottom: 42px;
}

.kart-text {
  max-width: 800px;
  margin: 0 auto;
}

/* ===== METADATA ===== */

.kart-meta {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 20px;
  padding: 18px 0;
  margin: 0 auto 28px;
  border-top: 1px solid #e6e6e6;
  border-bottom: 1px solid #e6e6e6;
}

.kart-meta-heading {
  font-size: 11px;
  font-weight: 700;
  letter-spacing: 1.5px;
  text-transform: uppercase;
  color: #999;
  margin-bottom: 8px;
}

.kart-meta-value {
  font-size: 14px;
  line-height: 1.6;
  color: #333;
}

/* ===== IMAGES ===== */

.kart-page figure {
  margin: 0;
  min-width: 0;
}

.kart-page img {
  display: block;
  width: 100%;
  height: auto;
  margin: 0 auto;
  border-radius: 4px;
}

.kart-page figcaption {
  font-size: 12px;
  line-height: 1.6;
  color: #888;
  margin-top: 9px;
}

.kart-page .kart-hero {
  width: 72%;
  max-width: 650px;
  margin: 24px auto;
}

.kart-page .kart-gallery {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 16px;
  width: 100%;
  max-width: 820px;
  margin: 24px auto;
  align-items: start;
}

.kart-page .kart-gallery img {
  width: 100%;
  height: 320px;
  object-fit: contain;
  object-position: center;
}

.kart-page .kart-full {
  width: 100%;
  max-width: 800px;
  margin: 24px auto;
}

/* ===== IMAGE PLACEHOLDERS ===== */

.kart-placeholder {
  width: 100%;
  min-height: 250px;
  aspect-ratio: 4 / 3;
  background: #f7f7f6;
  border: 1px dashed #d8d8d5;
  border-radius: 4px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 22px;
  color: #888;
}

.kart-placeholder strong {
  font-size: 14px;
  font-weight: 500;
  color: #555;
  margin-bottom: 7px;
}

.kart-placeholder span {
  font-size: 12px;
  line-height: 1.6;
}

/* ===== DESIGN HIGHLIGHTS ===== */

.kart-specs {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 16px;
  max-width: 800px;
  margin: 24px auto;
}

.kart-spec {
  background: #f7f7f6;
  padding: 24px 14px;
  border-radius: 4px;
}

.kart-spec-title {
  font-size: 17px;
  font-weight: 600;
  color: #333;
  margin-bottom: 7px;
}

.kart-spec-label {
  font-size: 12px;
  line-height: 1.6;
  color: #777;
}

/* ===== EQUATIONS ===== */

.kart-equations {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 16px;
  max-width: 760px;
  margin: 25px auto;
}

.kart-equation {
  background: #f7f7f6;
  border-radius: 5px;
  padding: 24px 14px;
}

.kart-equation-label {
  font-size: 11px;
  letter-spacing: 1px;
  text-transform: uppercase;
  color: #888;
  margin-bottom: 13px;
}

.kart-equation-formula {
  font-size: 19px;
  color: #333;
  line-height: 1.5;
}

.kart-equation-note {
  font-size: 12px;
  line-height: 1.7;
  color: #777;
  margin: 12px auto 0;
  max-width: 760px;
}

/* ===== DESIGN ITERATION ===== */

.kart-steps {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 14px;
  max-width: 800px;
  margin: 24px auto;
}

.kart-step {
  background: #f7f7f6;
  border-radius: 4px;
  padding: 22px 14px;
}

.kart-step-number {
  font-size: 12px;
  font-weight: 700;
  color: #888;
  letter-spacing: 1px;
  margin-bottom: 10px;
}

.kart-step-title {
  font-size: 15px;
  font-weight: 600;
  margin-bottom: 7px;
}

.kart-step-description {
  font-size: 12px;
  line-height: 1.6;
  color: #777;
}

/* ===== MOBILE ===== */

@media (max-width: 700px) {
  .kart-page {
    width: calc(100% - 36px);
    padding: 20px 0 35px;
  }

  .kart-page p {
    font-size: 15px;
  }

  .kart-meta {
    gap: 12px;
  }

  .kart-meta-value {
    font-size: 12px;
  }

  .kart-page .kart-hero {
    width: 100%;
  }

  .kart-page .kart-gallery,
  .kart-equations {
    grid-template-columns: 1fr;
  }

  .kart-page .kart-gallery {
    max-width: 380px;
  }

  .kart-page .kart-gallery img {
    height: auto;
    max-height: 360px;
  }

  .kart-specs,
  .kart-steps {
    grid-template-columns: 1fr;
  }
}


/* ===== AR KART VIDEO ===== */

.kart-page .kart-video {
  width: 75%;
  max-width: 620px;
  margin: 28px auto 12px;
  text-align: center;
}

.kart-page .kart-video video {
  display: block;
  width: 100%;
  height: auto;
  max-height: 420px;
  object-fit: contain;
  border-radius: 6px;
  background: #111;
}

.kart-page .kart-video figcaption {
  margin-top: 10px;
  font-size: 12px;
  color: #888;
}

@media (max-width: 700px) {
  .kart-page .kart-video {
    width: 100%;
  }
}

</style>

<div class="kart-page">

  <!-- ===== TITLE ===== -->

  <h1 class="kart-title">AR Kart</h1>

  <!-- ===== PROJECT OVERVIEW ===== -->

  <section id="overview">

    <div class="kart-meta">
      <div>
        <div class="kart-meta-heading">Role</div>
        <div class="kart-meta-value">
          Mechanical Design &amp; Prototyping
        </div>
      </div>

      <div>
        <div class="kart-meta-heading">Year</div>
        <div class="kart-meta-value">2025</div>
      </div>

      <div>
        <div class="kart-meta-heading">Team</div>
        <div class="kart-meta-value">
          Cornell Cup Robotics
        </div>
      </div>
    </div>

    <h2>Project Overview</h2>

    <div class="kart-text">
      <p>
        The AR Kart is a small robotic vehicle developed
        through Cornell Cup Robotics, combining a steering
        system, motor-driven drivetrain, and onboard camera
        for augmented reality applications.
      </p>

      <p>
        I focused on mechanical design and prototyping,
        particularly the steering mechanism, drivetrain
        integration, and component mounting. Using Fusion 360
        and 3D printing, I designed parts, assembled mechanisms,
        and worked through issues with alignment, friction,
        and clearance.
      </p>
    </div>

    <figure class="kart-hero">
      <img
        src="{{ '/assets/images/ar-kart.png' | relative_url }}"
        alt="AR Kart robotic vehicle"
      >
      <figcaption>
        Figure 1. AR Kart robotic vehicle.
      </figcaption>
    </figure>

  </section>

  <!-- ===== SYSTEM DESIGN ===== -->

  <section id="system">

    <h2>Mechanical System Design</h2>

    <div class="kart-text">
      <p>
        The vehicle combines steering, propulsion, and
        camera mounting in a compact assembly. A major
        challenge was arranging these components so that
        each mechanism could move without interfering
        with the others.
      </p>
    </div>

    <div class="kart-specs">

      <div class="kart-spec">
        <div class="kart-spec-title">Steering</div>
        <div class="kart-spec-label">
          Ackermann geometry with servo-driven linkages
        </div>
      </div>

      <div class="kart-spec">
        <div class="kart-spec-title">Drivetrain</div>
        <div class="kart-spec-label">
          Motor-driven wheel propulsion
        </div>
      </div>

      <div class="kart-spec">
        <div class="kart-spec-title">Modularity</div>
        <div class="kart-spec-label">
          Custom printed mounts and removable connections
        </div>
      </div>

    </div>

    <div class="kart-gallery">

      <figure>
        <div class="kart-placeholder">
          <strong>Full CAD Assembly</strong>
          <span>
            Add an isometric Fusion 360 view
            of the assembled vehicle
          </span>
        </div>
        <figcaption>
          Figure 2. Overall vehicle CAD assembly.
        </figcaption>
      </figure>

      <figure>
        <div class="kart-placeholder">
          <strong>Mechanical Layout</strong>
          <span>
            Add a top view showing the steering,
            drivetrain, and camera mounting positions
          </span>
        </div>
        <figcaption>
          Figure 3. Internal mechanical arrangement.
        </figcaption>
      </figure>

    </div>

  </section>

  <!-- ===== ACKERMANN STEERING ===== -->

  <section id="steering">

    <h2>Ackermann Steering Design</h2>

    <div class="kart-text">
      <p>
        One of the most interesting parts of the project
        was designing the front-wheel steering system.
        During a turn, the inside wheel follows a smaller
        radius than the outside wheel, so it needs to
        rotate through a larger steering angle.
      </p>

      <p>
        Ackermann geometry accounts for this difference
        through the positioning of the steering arms
        and linkages, helping reduce tire scrubbing
        and allowing smoother turns.
      </p>
    </div>

    <div class="kart-equations">

      <div class="kart-equation">
        <div class="kart-equation-label">
          Inside Wheel
        </div>
        <div class="kart-equation-formula">
          tan(&delta;<sub>in</sub>) =
          L / (R - W/2)
        </div>
      </div>

      <div class="kart-equation">
        <div class="kart-equation-label">
          Outside Wheel
        </div>
        <div class="kart-equation-formula">
          tan(&delta;<sub>out</sub>) =
          L / (R + W/2)
        </div>
      </div>

    </div>

    <div class="kart-equation-note">
      L = wheelbase &nbsp;·&nbsp;
      W = track width &nbsp;·&nbsp;
      R = turning radius measured to the midpoint
      of the rear axle
    </div>

    <div class="kart-text" style="margin-top: 22px;">
      <p>
        I considered how steering-arm placement,
        linkage geometry, and available space
        affected the wheel angles and the
        mechanism's range of motion.
      </p>
    </div>

    <div class="kart-gallery">

      <figure>
        <div class="kart-placeholder">
          <strong>Steering CAD</strong>
          <span>
            Add a close-up of the steering
            arms and linkage assembly
          </span>
        </div>
        <figcaption>
          Figure 4. Front steering mechanism.
        </figcaption>
      </figure>

      <figure>
        <div class="kart-placeholder">
          <strong>Steering Geometry</strong>
          <span>
            Add a top-view steering diagram
            or turning-position comparison
          </span>
        </div>
        <figcaption>
          Figure 5. Ackermann steering arrangement.
        </figcaption>
      </figure>

    </div>

  </section>

  <!-- ===== DRIVETRAIN ===== -->

  <section id="drivetrain">

    <h2>Drivetrain &amp; Motor Integration</h2>

    <div class="kart-text">
      <p>
        The drivetrain transfers motor rotation to
        the wheels. Integrating it with the steering
        system required careful attention to motor
        placement, wheel alignment, friction, and
        mechanical clearance.
      </p>

      <p>
        Because the vehicle was compact, even small
        adjustments to one component could affect
        the movement or positioning of another.
      </p>
    </div>

    <figure class="kart-full">
      <div class="kart-placeholder">
        <strong>Drivetrain Assembly</strong>
        <span>
          Add a CAD screenshot or photo showing
          the motor and wheel connections
        </span>
      </div>
      <figcaption>
        Figure 6. Drivetrain and motor integration.
      </figcaption>
    </figure>

  </section>

  <!-- ===== PROTOTYPING ===== -->

  <section id="prototyping">

    <h2>CAD &amp; Mechanical Prototyping</h2>

    <div class="kart-text">
      <p>
        I used Fusion 360 to design custom components
        and 3D printing to turn those designs into
        physical prototypes. Testing the printed
        parts helped identify fit issues that
        were not obvious in CAD.
      </p>

      <p>
        I made adjustments to part geometry,
        clearances, and connections based on
        how the components behaved during assembly.
      </p>
    </div>

    <div class="kart-steps">

      <div class="kart-step">
        <div class="kart-step-number">01</div>
        <div class="kart-step-title">Design</div>
        <div class="kart-step-description">
          Model parts and assemblies in Fusion 360
        </div>
      </div>

      <div class="kart-step">
        <div class="kart-step-number">02</div>
        <div class="kart-step-title">Prototype</div>
        <div class="kart-step-description">
          Print and assemble mechanical components
        </div>
      </div>

      <div class="kart-step">
        <div class="kart-step-number">03</div>
        <div class="kart-step-title">Improve</div>
        <div class="kart-step-description">
          Adjust fit, alignment, and clearance
        </div>
      </div>

    </div>

    <div class="kart-gallery">

      <figure>
        <div class="kart-placeholder">
          <strong>3D-Printed Components</strong>
          <span>
            Add a photo of the printed mounts,
            joints, or chassis parts
          </span>
        </div>
        <figcaption>
          Figure 7. Printed mechanical components.
        </figcaption>
      </figure>

      <figure>
        <div class="kart-placeholder">
          <strong>Prototype Assembly</strong>
          <span>
            Add a photo showing the
            assembled vehicle during testing
          </span>
        </div>
        <figcaption>
          Figure 8. Mechanical prototype assembly.
        </figcaption>
      </figure>

    </div>

  </section>

  <!-- ===== SNAP FITS ===== -->

  <section id="connections">

    <h2>Snap-Fit &amp; Modular Connections</h2>

    <div class="kart-text">
      <p>
        We used custom 3D-printed connections
        to make the vehicle easier to assemble
        and modify. Snap-fit features helped
        reduce the need for additional fasteners
        while allowing components to be removed.
      </p>

      <p>
        We worked with clearances around 0.30 mm
        for snap-fit features, then checked the
        physical fit during prototyping. Too
        little clearance made assembly difficult,
        while too much allowed unwanted movement.
      </p>
    </div>

    <div class="kart-gallery">

      <figure>
        <div class="kart-placeholder">
          <strong>Snap-Fit Detail</strong>
          <span>
            Add a CAD close-up of
            a snap-fit connection
          </span>
        </div>
        <figcaption>
          Figure 9. Snap-fit connection geometry.
        </figcaption>
      </figure>

      <figure>
        <div class="kart-placeholder">
          <strong>Physical Connection</strong>
          <span>
            Add a photo of the printed
            connection during assembly
          </span>
        </div>
        <figcaption>
          Figure 10. Printed modular connection.
        </figcaption>
      </figure>

    </div>

  </section>

  <!-- ===== CAMERA MOUNT ===== -->

  <section id="camera">

    <h2>Camera Mounting System</h2>

    <div class="kart-text">
      <p>
        The vehicle included a camera for capturing
        its surroundings. The mount needed to
        provide a stable viewing position without
        interfering with the steering or drivetrain.
      </p>

      <p>
        I considered camera placement, field of view,
        vibration, and ease of assembly when
        integrating the mount into the vehicle.
      </p>
    </div>

    <figure class="kart-full">
      <div class="kart-placeholder">
        <strong>Camera Mount</strong>
        <span>
          Add a CAD screenshot or photograph
          of the camera mounting assembly
        </span>
      </div>
      <figcaption>
        Figure 11. Camera mounting system.
      </figcaption>
    </figure>

  </section>

  <!-- ===== TESTING ===== -->

  <section id="testing">

    <h2>Testing &amp; Design Iteration</h2>

    <div class="kart-text">
      <p>
        Testing focused on whether the steering
        and drivetrain could move smoothly
        without binding. We checked linkage
        alignment, joint friction, and clearance
        throughout the steering motion.
      </p>

      <p>
        When parts did not move as expected,
        we inspected the physical assembly,
        identified possible interference,
        and revised the CAD geometry before
        printing updated components.
      </p>
    </div>

    <div class="kart-gallery">

      <figure>
        <div class="kart-placeholder">
          <strong>Steering Test</strong>
          <span>
            Add a photo or frame showing
            the steering mechanism in motion
          </span>
        </div>
        <figcaption>
          Figure 12. Steering mechanism testing.
        </figcaption>
      </figure>

      <figure>
        <div class="kart-placeholder">
          <strong>Updated Prototype</strong>
          <span>
            Add a photo of the revised
            mechanical assembly
          </span>
        </div>
        <figcaption>
          Figure 13. Updated prototype after iteration.
        </figcaption>
      </figure>

    </div>

    <figure class="kart-video">
    <video controls playsinline preload="metadata">
        <source
        src="{{ '/assets/videos/ar-kart.mp4' | relative_url }}"
        type="video/mp4"
        >
        Your browser does not support video playback.
    </video>

    <figcaption>
        Figure 14. AR Kart prototype demonstrating
        steering and drivetrain operation.
    </figcaption>
</figure>

  </section>

  <!-- ===== RESULTS ===== -->

  <section id="results">

    <h2>Engineering Takeaways</h2>

    <div class="kart-text">
      <p>
        This project showed me how closely connected
        steering geometry, drivetrain performance,
        tolerances, and assembly really are.
        A component can look correct in CAD
        but still cause friction or interference
        once it is physically assembled.
      </p>

      <p>
        The most valuable part was working through
        those problems firsthand, from adjusting
        steering linkages to improving printed
        connections. It strengthened my skills
        in mechanical design, prototyping,
        and troubleshooting moving systems.
      </p>
    </div>

  </section>

</div>
