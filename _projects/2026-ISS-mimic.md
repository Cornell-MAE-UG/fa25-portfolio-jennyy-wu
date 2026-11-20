---
layout: project
title: ISS Mimic
permalink: /projects/iss-mimic/
description: Cornell Cup Robotics — Mechanical Design and Prototyping
technologies: [Fusion 360, CAD, 3D Printing, Gear Design, Mechanical Assembly, Robotics]
---

<style>
/* ===== ISS MIMIC PROJECT PAGE ===== */

.iss-page {
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

.iss-page * {
  box-sizing: border-box;
}

/* ===== TITLES AND TEXT ===== */

.iss-page .iss-main-title {
  font-family: Georgia, "Times New Roman", serif;
  font-size: clamp(44px, 5vw, 58px);
  font-weight: 700;
  letter-spacing: -0.045em;
  line-height: 1.1;
  color: #222;
  text-align: center;
  margin: 0 auto 14px;
}

.iss-page h2 {
  font-family: Georgia, "Times New Roman", serif;
  font-size: clamp(29px, 3vw, 38px);
  font-weight: 400;
  letter-spacing: -0.035em;
  line-height: 1.25;
  color: #171717;
  text-align: center;
  margin: 0 0 25px;
}

.iss-page h3 {
  font-family: "Helvetica Neue", Arial, sans-serif;
  font-size: 21px;
  font-weight: 500;
  letter-spacing: -0.025em;
  color: #222;
  text-align: center;
  margin: 34px 0 16px;
}

.iss-page p {
  font-size: 16px;
  line-height: 1.85;
  color: #444;
  text-align: center;
  margin: 0 0 20px;
}

.iss-page section {
  margin-bottom: 85px;
}

.iss-text {
  max-width: 800px;
  margin: 0 auto;
}

/* ===== PROJECT METADATA ===== */

.iss-page .iss-meta {
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

.iss-meta > div {
  min-width: 0;
}

.iss-meta-heading {
  font-size: 11px;
  font-weight: 700;
  letter-spacing: 1.5px;
  text-transform: uppercase;
  color: #999;
  margin-bottom: 8px;
}

.iss-meta-value {
  font-size: 15px;
  line-height: 1.6;
  color: #333;
}

/* ===== PHOTOS AND FIGURES ===== */

.iss-page figure {
  margin: 0;
  min-width: 0;
  text-align: center;
}

.iss-page img {
  display: block;
  width: 100%;
  height: auto;
  margin: 0 auto;
  border-radius: 4px;
}

.iss-page figcaption {
  font-size: 12px;
  line-height: 1.65;
  color: #888;
  margin-top: 11px;
  text-align: center;
}

.iss-page .iss-full {
  width: 100%;
  margin: 32px auto 40px;
}

/* Main project photo: smaller and centered */

.iss-page .iss-hero {
  width: 70%;
  max-width: 630px;
  margin: 35px auto 40px;
}

.iss-page .iss-hero img {
  width: 100%;
}

/* ===== IMAGE GALLERIES ===== */

.iss-page .iss-gallery {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 28px;
  width: 100%;
  margin: 32px auto 38px;
}

.iss-page .iss-gallery.three {
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 20px;
}

/* ===== IMAGE PLACEHOLDERS ===== */

.iss-placeholder {
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

.iss-placeholder.wide {
  aspect-ratio: 16 / 9;
}

.iss-placeholder.square {
  aspect-ratio: 1 / 1;
}

.iss-placeholder-icon {
  font-size: 27px;
  font-weight: 300;
  color: #aaa;
  margin-bottom: 13px;
}

.iss-placeholder-title {
  font-size: 14px;
  font-weight: 600;
  color: #777;
  margin-bottom: 8px;
}

.iss-placeholder-note {
  font-size: 12px;
  line-height: 1.6;
  color: #aaa;
  max-width: 330px;
}

/* ===== ENGINEERING SPECIFICATIONS ===== */

.iss-specs {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 18px;
  margin: 32px 0;
}

.iss-spec {
  background: #f7f7f6;
  padding: 25px;
  border-radius: 4px;
  text-align: center;
}

.iss-spec-number {
  font-size: 31px;
  font-weight: 600;
  letter-spacing: -1px;
  color: #222;
  margin-bottom: 7px;
}

.iss-spec-name {
  font-size: 12px;
  line-height: 1.5;
  color: #777;
}

.iss-equation {
  background: #f7f7f6;
  padding: 30px;
  margin: 32px 0;
  border-radius: 4px;
  text-align: center;
}

.iss-equation-main {
  font-size: clamp(19px, 2.8vw, 28px);
  font-weight: 600;
  color: #222;
}

.iss-equation-note {
  font-size: 12px;
  color: #888;
  margin-top: 10px;
}

/* ===== MOBILE ===== */

@media (max-width: 700px) {
  .iss-page {
    width: calc(100% - 36px);
    padding: 20px 0 65px;
  }

  .iss-page section {
    margin-bottom: 65px;
  }

  .iss-page .iss-meta {
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 10px;
  }

  .iss-meta-value {
    font-size: 13px;
  }

  .iss-page .iss-hero {
    width: 100%;
    max-width: 100%;
  }

  .iss-page .iss-gallery,
  .iss-page .iss-gallery.three {
    grid-template-columns: 1fr;
  }

  .iss-specs {
    grid-template-columns: 1fr;
  }

  .iss-page p {
    font-size: 15px;
  }
}
</style>

<div class="iss-page">

  <!-- ===== MAIN TITLE ===== -->

  <h1 class="iss-main-title">ISS Mimic</h1>


  <!-- ===== PROJECT OVERVIEW ===== -->

  <section>

    <div class="iss-meta">
      <div>
        <div class="iss-meta-heading">Role</div>
        <div class="iss-meta-value">
          Mechanical Design &amp; Prototyping
        </div>
      </div>

      <div>
        <div class="iss-meta-heading">Year</div>
        <div class="iss-meta-value">2025–2026</div>
      </div>

      <div>
        <div class="iss-meta-heading">Team</div>
        <div class="iss-meta-value">
          Cornell Cup Robotics
        </div>
      </div>
    </div>

    <h2>Project Overview</h2>

    <div class="iss-text">
      <p>
        The ISS Mimic is a Cornell Cup Robotics project
        designed to recreate the real-time movement of
        the International Space Station using an XRP
        robotics platform. Developed in collaboration
        with Boeing and Intel, the project combines
        rotational and linear motion to create an
        interactive representation of the ISS.
      </p>

      <p>
        I worked on the mechanical design and prototyping
        of the robot, focusing on the rotating pillar,
        gear-driven motor system, and detachable two-axis
        gantry. My work involved designing components
        in Fusion 360, 3D printing prototypes, assembling
        mechanisms, and troubleshooting mechanical issues
        during testing.
      </p>
    </div>

    <figure class="iss-hero">
      <img
        src="{{ '/assets/images/iss-mimic.jpg' | relative_url }}"
        alt="ISS Mimic robotic system"
        loading="lazy"
      >
      <figcaption>
        Figure 1. ISS Mimic robotic system.
      </figcaption>
    </figure>

  </section>


  <!-- ===== CAD DRAWINGS ===== -->

  <section>

    <h2>Fusion 360 CAD Drawings</h2>

    <div class="iss-text">
      <p>
        I used Fusion 360 to design and modify the
        mechanical components of the ISS Mimic.
        The assembly includes a rotating pillar,
        motor-driven spur gears, a belt-driven gantry,
        and custom 3D-printed mounting components.
      </p>

      <p>
        The CAD models helped us understand how the
        mechanisms fit together, check clearances,
        and plan the assembly before manufacturing
        the parts.
      </p>
    </div>

    <figure class="iss-full">
      <div class="iss-placeholder wide">
        <div class="iss-placeholder-icon">+</div>
        <div class="iss-placeholder-title">
          Full Assembly — Isometric View
        </div>
        <div class="iss-placeholder-note">
          Add a Fusion 360 rendering of the
          complete ISS Mimic assembly.
        </div>
      </div>
      <figcaption>
        Figure 2. Isometric CAD view of the complete assembly.
      </figcaption>
    </figure>

    <div class="iss-gallery">

      <figure>
        <div class="iss-placeholder">
          <div class="iss-placeholder-icon">+</div>
          <div class="iss-placeholder-title">
            Exploded Assembly View
          </div>
          <div class="iss-placeholder-note">
            Exploded CAD showing the motor,
            gears, pillar, and mounts.
          </div>
        </div>
        <figcaption>
          Figure 3. Exploded view of the mechanical components.
        </figcaption>
      </figure>

      <figure>
        <div class="iss-placeholder">
          <div class="iss-placeholder-icon">+</div>
          <div class="iss-placeholder-title">
            Side / Section View
          </div>
          <div class="iss-placeholder-note">
            Side or section view showing the
            internal arrangement and clearances.
          </div>
        </div>
        <figcaption>
          Figure 4. Internal arrangement of the assembly.
        </figcaption>
      </figure>

    </div>

  </section>


  <!-- ===== SPUR GEAR DESIGN ===== -->

  <section>

    <h2>Rotating Pillar &amp; Spur Gear Design</h2>

    <div class="iss-text">
      <p>
        One of the main engineering challenges was
        getting the motor to rotate the pillar properly.
        During initial testing, the motor attempted
        to turn, but the pillar barely moved and
        would sometimes stall.
      </p>

      <p>
        To improve the mechanism, I worked on a
        spur gear train consisting of an 11-tooth
        pinion and a 36-tooth driven gear.
        The smaller pinion transfers motion from
        the motor to the larger gear connected
        to the rotating pillar.
      </p>

      <p>
        This arrangement reduces rotational speed
        while increasing the available output torque,
        making it easier for the motor to rotate
        the assembly.
      </p>
    </div>

    <figure class="iss-full">
      <div class="iss-placeholder wide">
        <div class="iss-placeholder-icon">+</div>
        <div class="iss-placeholder-title">
          Spur Gear Technical Drawing
        </div>
        <div class="iss-placeholder-note">
          Add an annotated drawing showing the
          pinion, driven gear, pitch circles,
          tooth profiles, pressure angle,
          and center distance.
        </div>
      </div>
      <figcaption>
        Figure 5. Spur gear geometry and design parameters.
      </figcaption>
    </figure>

    <h3>Gear Ratio Calculations</h3>

    <div class="iss-specs">
      <div class="iss-spec">
        <div class="iss-spec-number">11</div>
        <div class="iss-spec-name">Pinion teeth</div>
      </div>

      <div class="iss-spec">
        <div class="iss-spec-number">36</div>
        <div class="iss-spec-name">Driven gear teeth</div>
      </div>

      <div class="iss-spec">
        <div class="iss-spec-number">3.27:1</div>
        <div class="iss-spec-name">Gear reduction</div>
      </div>
    </div>

    <div class="iss-equation">
      <div class="iss-equation-main">
        Gear Ratio = 36 / 11 = 3.27
      </div>
      <div class="iss-equation-note">
        Ideal torque multiplication = 3.27×,
        neglecting mechanical losses.
      </div>
    </div>

    <div class="iss-text">
      <p>
        The 3.27:1 gear reduction decreases the
        output rotational speed by approximately
        69.4% while ideally multiplying the
        output torque by 3.27.
      </p>

      <p>
        I also worked on positioning the gears
        and motor mount to maintain proper gear
        engagement. Small changes in spacing
        can affect how smoothly the gears mesh,
        so alignment and clearance were important
        considerations during assembly.
      </p>
    </div>

    <div class="iss-gallery">

      <figure>
        <div class="iss-placeholder">
          <div class="iss-placeholder-icon">+</div>
          <div class="iss-placeholder-title">
            Spur Gear CAD Model
          </div>
          <div class="iss-placeholder-note">
            Close-up Fusion 360 view of the
            11-tooth pinion and 36-tooth gear.
          </div>
        </div>
        <figcaption>
          Figure 6. CAD model of the spur gear pair.
        </figcaption>
      </figure>

      <figure>
        <div class="iss-placeholder">
          <div class="iss-placeholder-icon">+</div>
          <div class="iss-placeholder-title">
            Physical Gear Assembly
          </div>
          <div class="iss-placeholder-note">
            Photo of the 3D-printed gears installed
            in the rotating pillar mechanism.
          </div>
        </div>
        <figcaption>
          Figure 7. Manufactured spur gear assembly.
        </figcaption>
      </figure>

    </div>

  </section>


  <!-- ===== MOTOR MOUNT ===== -->

  <section>

    <h2>Motor Mount Design &amp; Assembly</h2>

    <div class="iss-text">
      <p>
        Another challenge involved designing a
        motor mount that could fit within the
        surrounding assembly while maintaining
        proper gear alignment.
      </p>

      <p>
        The original motor mount fit in the
        Fusion 360 model, but it was difficult
        to install because nearby components
        blocked the assembly path.
        Although everything appeared to fit in CAD,
        there was not enough room to physically
        position the motor during installation.
      </p>

      <p>
        I redesigned the motor positioning by moving
        the mount toward the side of the assembly.
        This improved access during installation
        while keeping the motor aligned with
        the driven gear.
      </p>
    </div>

    <h3>Design Iterations</h3>

    <div class="iss-gallery">

      <figure>
        <div class="iss-placeholder">
          <div class="iss-placeholder-icon">+</div>
          <div class="iss-placeholder-title">
            Original Motor Mount
          </div>
          <div class="iss-placeholder-note">
            CAD of the original centrally
            positioned motor mount.
          </div>
        </div>
        <figcaption>
          Figure 8. Original motor mount with limited installation access.
        </figcaption>
      </figure>

      <figure>
        <div class="iss-placeholder">
          <div class="iss-placeholder-icon">+</div>
          <div class="iss-placeholder-title">
            Redesigned Motor Mount
          </div>
          <div class="iss-placeholder-note">
            Updated CAD showing the motor
            repositioned toward the side.
          </div>
        </div>
        <figcaption>
          Figure 9. Revised motor mount with improved assembly access.
        </figcaption>
      </figure>

    </div>

  </section>


  <!-- ===== TWO-AXIS GANTRY ===== -->

  <section>

    <h2>Two-Axis Belt-Driven Gantry</h2>

    <div class="iss-text">
      <p>
        In addition to the rotating pillar,
        the ISS Mimic uses a belt-driven gantry
        to provide movement along the X and Y axes.
        Motors rotate pulleys connected to belts,
        while rails guide the moving assembly
        and help maintain alignment.
      </p>

      <p>
        I worked on the detachable mounting system
        and 3D-printed connecting components
        so the robot could be removed from the
        gantry without rebuilding the entire assembly.
      </p>

      <p>
        The design required considering mounting
        strength, mechanical alignment, clearance
        between moving components, and ease of
        installation and removal.
      </p>
    </div>

    <div class="iss-gallery">

      <figure>
        <div class="iss-placeholder">
          <div class="iss-placeholder-icon">+</div>
          <div class="iss-placeholder-title">
            Gantry CAD Assembly
          </div>
          <div class="iss-placeholder-note">
            Isometric Fusion 360 view of the
            two-axis gantry and belt system.
          </div>
        </div>
        <figcaption>
          Figure 10. CAD model of the belt-driven gantry.
        </figcaption>
      </figure>

      <figure>
        <div class="iss-placeholder">
          <div class="iss-placeholder-icon">+</div>
          <div class="iss-placeholder-title">
            Physical Gantry Assembly
          </div>
          <div class="iss-placeholder-note">
            Photo showing the assembled rails,
            belts, pulleys, and mounting structure.
          </div>
        </div>
        <figcaption>
          Figure 11. Assembled two-axis gantry.
        </figcaption>
      </figure>

    </div>

    <h3>Detachable Mounting Mechanism</h3>

    <div class="iss-text">
      <p>
        The mounting connection needed to hold
        the robot securely during operation while
        still allowing it to be detached when needed.
      </p>

      <p>
        I designed connecting components with
        attention to alignment, fit, and assembly.
        Snap-fit features and custom mounting
        geometry helped make the connection
        practical for repeated use.
      </p>
    </div>

    <div class="iss-gallery">

      <figure>
        <div class="iss-placeholder">
          <div class="iss-placeholder-icon">+</div>
          <div class="iss-placeholder-title">
            Detachable Mount CAD
          </div>
          <div class="iss-placeholder-note">
            CAD close-up of the connection
            and mounting features.
          </div>
        </div>
        <figcaption>
          Figure 12. CAD design of the detachable mounting system.
        </figcaption>
      </figure>

      <figure>
        <div class="iss-placeholder">
          <div class="iss-placeholder-icon">+</div>
          <div class="iss-placeholder-title">
            Mounting Connection Detail
          </div>
          <div class="iss-placeholder-note">
            Physical photo showing how the
            robot attaches to the gantry.
          </div>
        </div>
        <figcaption>
          Figure 13. Physical detachable mounting connection.
        </figcaption>
      </figure>

    </div>

  </section>


  <!-- ===== TESTING AND RESULTS ===== -->

  <section>

    <h2>Testing &amp; Results</h2>

    <div class="iss-text">
      <p>
        Testing focused on identifying mechanical
        issues that prevented the robot from moving
        reliably. For the rotating pillar,
        I investigated the gear engagement,
        motor positioning, and mechanical resistance
        that could be contributing to the stalling.
      </p>

      <p>
        After redesigning and printing the gear
        assembly, we installed the new components
        and tested the mechanism again.
        The revised gear train successfully
        rotated the pillar, resolving the
        original issue.
      </p>

      <p>
        The process involved repeatedly moving
        between CAD, 3D printing, assembly,
        and physical testing. Each iteration
        helped us identify problems and
        improve the reliability of the mechanism.
      </p>
    </div>

    <figure class="iss-full">
      <div class="iss-placeholder wide">
        <div class="iss-placeholder-icon">+</div>
        <div class="iss-placeholder-title">
          Final Working Mechanism
        </div>
        <div class="iss-placeholder-note">
          Add a photograph showing the completed
          rotating pillar and gear assembly.
        </div>
      </div>
      <figcaption>
        Figure 14. Completed rotating pillar mechanism after redesign.
      </figcaption>
    </figure>

    <h3>Video of the Mechanism in Action</h3>

    <div class="iss-text">
      <p>
        The video below demonstrates the redesigned
        gear assembly driving the rotating pillar.
        Unlike the initial prototype, the updated
        mechanism was able to rotate successfully
        during testing.
      </p>
    </div>

    <figure class="iss-full">
      <div class="iss-placeholder wide">
        <div class="iss-placeholder-icon">▶</div>
        <div class="iss-placeholder-title">
          Rotating Pillar Test Video
        </div>
        <div class="iss-placeholder-note">
          Replace with an MP4 video or embedded
          video showing the working mechanism.
        </div>
      </div>
      <figcaption>
        Video 1. Testing the redesigned rotating pillar assembly.
      </figcaption>
    </figure>

  </section>

</div>
