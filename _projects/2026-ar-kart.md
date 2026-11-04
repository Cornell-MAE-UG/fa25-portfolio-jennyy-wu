---
layout: project
title: AR Kart XRP
permalink: /projects/ar-kart/
description: Cornell Cup Robotics — Mechanical Design, Steering, and Prototyping
technologies: [Fusion 360, CAD, 3D Printing, Ackermann Steering, Drivetrain, Robotics]
image: /assets/images/ar-kart.png
---

<style>
.page-content,
.wrapper,
.container {
    max-width: 900px !important;
    width: 92% !important;
}

.project-detail {
    font-family: "Helvetica Neue", Arial, sans-serif;
    line-height: 1.8;
    color: #333;
}

.project-detail h2 {
    font-size: 27px;
    font-weight: 650;
    margin-top: 45px;
    margin-bottom: 16px;
    letter-spacing: -0.5px;
}

.project-detail h3 {
    font-size: 20px;
    margin-top: 28px;
    margin-bottom: 12px;
}

.project-detail p {
    margin-bottom: 18px;
}

.project-detail ul {
    padding-left: 25px;
    margin-bottom: 22px;
}

.project-detail li {
    margin-bottom: 8px;
}

.project-detail hr {
    border: none;
    border-top: 1px solid #ddd;
    margin: 45px 0;
}

.project-detail .intro {
    font-size: 18px;
    line-height: 1.8;
    margin-bottom: 35px;
}

.project-detail .equation {
    text-align: center;
    font-size: 21px;
    padding: 20px;
    background: #f5f5f5;
    border-radius: 8px;
    margin: 25px 0;
}
</style>

<div class="project-detail">

<p class="intro">
The AR Kart XRP is a Cornell Cup Robotics project focused on
designing and building a small robotic vehicle with a modular
mechanical system and a camera for augmented reality applications.

I worked on the mechanical design and prototyping of the car,
particularly its steering system, drivetrain integration, and
component mounting. My work involved using Fusion 360 to
design parts, 3D printing prototypes, assembling mechanisms,
and troubleshooting problems with alignment, friction,
and mechanical clearance.
</p>

<hr>

<h2>System Description</h2>

<p>
The AR Kart combines steering, propulsion, and a camera
mounting system into a compact robotic vehicle.
</p>

<p>The mechanical system includes:</p>

<ul>
    <li>Ackermann steering geometry for the front wheels</li>
    <li>A servo-driven steering mechanism</li>
    <li>A motor-driven drivetrain for vehicle movement</li>
    <li>Custom 3D-printed mechanical components</li>
    <li>Snap-fit and other modular connections</li>
    <li>A camera mounting system</li>
    <li>An XRP robotics platform</li>
</ul>

<p>
One of the main design challenges was fitting these
components into a small vehicle while ensuring that
the steering and drivetrain could move freely.
</p>

<hr>

<h2>Ackermann Steering Design</h2>

<p>
One of the most interesting parts of the project was
designing the steering system using Ackermann geometry.
</p>

<p>
When a car turns, the inside front wheel follows a
smaller turning radius than the outside front wheel.
Because of this, the inside wheel needs to turn at
a sharper angle.
</p>

<p>
Ackermann steering accounts for this difference
through the geometry of the steering arms and linkages.
This helps the wheels follow their intended paths
and reduces tire scrubbing during turns.
</p>

<h3>Steering Geometry</h3>

<p>
The ideal steering angles depend on the vehicle's
wheelbase, track width, and turning radius.
</p>

<div class="equation">
    tan(&delta;<sub>in</sub>) =
    L / (R - W/2)
</div>

<div class="equation">
    tan(&delta;<sub>out</sub>) =
    L / (R + W/2)
</div>

<p>Where:</p>

<ul>
    <li>L = wheelbase</li>
    <li>W = track width</li>
    <li>R = turning radius measured to the midpoint of the rear axle</li>
    <li>&delta;<sub>in</sub> = inside wheel steering angle</li>
    <li>&delta;<sub>out</sub> = outside wheel steering angle</li>
</ul>

<p>
I considered how the positions of the steering arms
and linkages would affect the wheel angles and
how much room the mechanism needed to move.
</p>

<hr>

<h2>Drivetrain and Motor Integration</h2>

<p>
The drivetrain transfers rotational motion from
the motor to the wheels, allowing the car to move.
</p>

<p>
An important part of the design was making sure
the drivetrain and steering components could fit
together without interfering with one another.
</p>

<p>Important considerations included:</p>

<ul>
    <li>Motor mounting and alignment</li>
    <li>Available torque for moving the vehicle</li>
    <li>Friction within the drivetrain</li>
    <li>Wheel size and ground clearance</li>
    <li>Space for the steering linkages</li>
    <li>Ease of assembly and maintenance</li>
</ul>

<p>
Because the car was relatively compact, even
small changes to one component could affect
the positioning or movement of another.
</p>

<hr>

<h2>CAD and Mechanical Prototyping</h2>

<p>
I used Fusion 360 to design and modify mechanical
components for the vehicle.
</p>

<p>
The parts were manufactured using 3D printing,
which allowed us to quickly test designs,
assemble them, and make improvements.
</p>

<p>
One important lesson was that parts that appear
to fit correctly in CAD do not always behave
the same way after printing.
</p>

<p>
Small differences in dimensions, alignment,
and clearance can create friction or prevent
moving components from operating smoothly.
</p>

<h3>Design Considerations</h3>

<ul>
    <li>Clearance between moving components</li>
    <li>Alignment of steering joints and linkages</li>
    <li>Print orientation and part strength</li>
    <li>Fit between connected components</li>
    <li>Assembly and disassembly</li>
    <li>Strength of mounting connections</li>
</ul>

<p>
I made adjustments to component geometry
and connections based on how the printed
parts behaved during assembly.
</p>

<hr>

<h2>Snap-Fit and Modular Connections</h2>

<p>
We used 3D-printed connections to make the
vehicle easier to assemble and modify.
</p>

<p>
Snap-fit connections were especially useful
because they allowed components to be joined
without requiring additional fasteners
in every location.
</p>

<p>
However, snap-fits also required careful
consideration of material flexibility,
clearance, and strength.
</p>

<p>
For our printed components, we worked with
clearances around 0.30 mm for snap-fit features,
then checked the physical fit during prototyping.
</p>

<p>
If a connection was too tight, it could be
difficult to assemble or could break.
If it was too loose, the component could
move unexpectedly during operation.
</p>

<hr>

<h2>Camera Mounting System</h2>

<p>
The AR Kart also included a camera mounting
system for capturing the vehicle's surroundings.
</p>

<p>
The mechanical design needed to provide a
stable mounting position while keeping the
camera clear of the steering and drivetrain.
</p>

<p>Important considerations included:</p>

<ul>
    <li>Camera position and field of view</li>
    <li>Mounting stability</li>
    <li>Vibration during movement</li>
    <li>Clearance from other components</li>
    <li>Ease of mounting and removal</li>
</ul>

<p>
The camera mount was another example of how
the design of one component needed to account
for the rest of the vehicle.
</p>

<hr>

<h2>Testing and Troubleshooting</h2>

<p>
Testing focused on making sure the steering
and drivetrain mechanisms could move smoothly
without binding or interfering with each other.
</p>

<p>
Some of the main issues we considered were
friction at the steering joints, alignment
of the linkages, and clearance between parts.
</p>

<h3>Steering Troubleshooting</h3>

<p>
When a mechanism did not move as expected,
we examined whether the components were
properly aligned and whether there was
enough clearance for the full steering motion.
</p>

<p>
This involved checking the physical assembly,
identifying possible interference,
and adjusting the CAD geometry before
printing updated parts.
</p>

<h3>Design Iteration</h3>

<p>
Our general process involved:
</p>

<ul>
    <li>Designing mechanical components in Fusion 360</li>
    <li>3D printing the parts</li>
    <li>Assembling the vehicle</li>
    <li>Checking fit and mechanical movement</li>
    <li>Identifying issues with friction or clearance</li>
    <li>Making design adjustments</li>
</ul>

<p>
This iterative process helped us understand
how small changes in component geometry
could affect the performance of the
entire assembly.
</p>

<hr>

<h2>Engineering Lessons</h2>

<p>
The AR Kart project taught me that even
a relatively simple vehicle requires
careful mechanical design.
</p>

<p>
Steering geometry, drivetrain performance,
component tolerances, and assembly all
affect one another.
</p>

<p>
I also learned how important it is to
consider the actual motion of an assembly,
rather than only checking whether the
components fit together in CAD.
</p>

<p>
Most importantly, this project strengthened
my skills in mechanical design, 3D printing,
prototyping, and troubleshooting while
giving me experience working with multiple
connected mechanical systems.
</p>

</div>
