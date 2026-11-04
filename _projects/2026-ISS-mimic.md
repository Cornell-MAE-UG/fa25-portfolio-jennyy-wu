---
layout: project
title: ISS Mimic
permalink: /projects/iss-mimic/
description: Cornell Cup Robotics — Mechanical Design and Prototyping
technologies: [Fusion 360, CAD, 3D Printing, Gear Design, Mechanical Assembly, Robotics]
image: /assets/images/iss-mimic.jpg
---

<style>
.page-content,
.wrapper,
.container {
    max-width: 800px !important;
    width: 92% !important;
}
</style>
<p style="max-width: 850px; margin: 0 auto 30px auto; font-size: 18px;">
The ISS Mimic is a Cornell Cup Robotics project designed to recreate the real-time movement of the International Space Station using an XRP robotics platform.

I worked on the mechanical design and prototyping of the robot, focusing on a 360-degree rotating pillar, a gear-driven motor system, and a detachable two-axis gantry. My work involved designing components in Fusion 360, 3D printing prototypes, assembling mechanisms, and troubleshooting mechanical issues.
</p>

---

## System Description

The ISS Mimic combines rotational and linear motion to represent the movement of the International Space Station.

The mechanical system includes:

- A rotating pillar that allows 360-degree rotation
- A motor-driven gear train that transfers torque to the pillar
- A two-axis belt-driven gantry for movement along the X and Y axes
- A detachable mounting system that allows the robot to be transferred between configurations
- Custom 3D-printed mounts and connecting components

My main contributions were designing the rotating pillar mechanism, improving the gear train, and developing mechanical connections for the detachable gantry.

---

## Rotating Pillar and Gear Design

One of the main engineering challenges was getting the motor to rotate the pillar properly.

The original mechanism struggled to provide enough torque to rotate the assembly reliably.

To address this, I worked on a gear train consisting of:

- 11-tooth pinion gear
- 36-tooth driven gear
- Gear ratio of approximately 3.27:1

The gear ratio was calculated as:

Gear Ratio = 36 / 11 = 3.27

This gear reduction decreased the output rotational speed while increasing the available torque.

Ideally, the output torque increases by a factor of approximately 3.27, before accounting for mechanical losses.

I also worked on the positioning of the gears and motor mount to ensure proper engagement and smooth rotation.

---

## Motor Mount Design and Assembly

Another challenge involved designing a motor mount that could fit within the surrounding assembly.

Although the original mount fit in the Fusion 360 CAD model, it could not be installed easily because nearby components blocked the assembly path.

I redesigned the motor positioning to make the mount easier to install while maintaining proper gear alignment.

This taught me that a design must not only fit in CAD but also be practical to manufacture and assemble.

---

## Two-Axis Gantry System

The ISS Mimic also uses a belt-driven gantry to provide movement along two axes.

Motors rotate pulleys, which drive belts connected to the moving assembly. Rails guide the movement and help maintain alignment.

I worked on the detachable mounting system and 3D-printed connecting components so the robot could be removed from the gantry without rebuilding the entire assembly.

This required considering:

- Mechanical alignment
- Mounting strength
- Clearance between moving parts
- Ease of assembly and removal
- Compatibility with the XRP platform

---

## CAD and 3D Printing

I used Fusion 360 to design and modify mechanical components throughout the project.

The parts were manufactured using 3D printing, which allowed us to test different designs and make adjustments quickly.

Important design considerations included:

- Gear spacing and alignment
- Clearance between moving components
- Snap-fit connections
- Print orientation and support structures
- Ease of assembly

Several components required changes after physical testing because their real-world fit differed from what we expected in CAD.

---

## Testing and Troubleshooting

Testing focused on identifying mechanical issues that prevented the robot from moving properly.

For the rotating pillar, I investigated the torque required to start rotation and used that information to guide the gear reduction design.

I also checked the fit of the motor mount, gear engagement, and clearance between components.

The process involved repeatedly designing, printing, assembling, and adjusting components.

---

## Engineering Lessons

This project taught me the importance of designing mechanical systems with both performance and assembly in mind.

I learned how gear ratios affect torque and speed, how small alignment issues can affect mechanical motion, and why physical prototyping is essential even when a design looks correct in CAD.

Most importantly, I gained experience taking a mechanical design from an initial idea through CAD, manufacturing, assembly, and troubleshooting.