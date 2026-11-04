---
layout: project
title: Submersible XRP
description: Cornell Cup Robotics — Underwater Robotics and Mechanical Design
technologies: [Fusion 360, CAD, 3D Printing, Rack-and-Pinion, Buoyancy, Waterproofing, Robotics]
image: /assets/images/submersible.jpeg
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
The Submersible XRP is a Cornell Cup Robotics project focused on developing an underwater robot capable of collecting water samples for microplastics research in collaboration with EarthEcho.

I worked on the mechanical design and prototyping of the robot, particularly its waterproof housing and syringe-based ballast system. My work involved designing components in Fusion 360, 3D printing prototypes, assembling mechanical systems, and troubleshooting issues related to waterproofing and buoyancy.
</p>

---

## System Description

The Submersible XRP is designed to travel underwater, control its depth, and collect water samples for microplastics analysis.

The mechanical system includes:

- A waterproof cylindrical housing that protects the electronics
- Two thrusters for underwater movement
- Two syringe-based ballast mechanisms for controlling buoyancy
- A separate syringe for collecting water samples
- N20 motors and rack-and-pinion mechanisms for moving the syringe plungers
- Internal mounting trays for the electronics and XRP components

One of the main design challenges was fitting all these components inside a compact, waterproof housing while keeping the robot capable of sinking and rising.

---

## Syringe-Based Ballast System

To control the robot's buoyancy, we designed a ballast system using two syringes driven by N20 motors and rack-and-pinion mechanisms.

The motor rotates a pinion gear, which moves a rack connected to the syringe plunger. This converts rotational motion into linear motion.

When the plunger pulls back, the syringe takes in water, increasing the robot's total mass and helping it sink.

When the plunger pushes forward, water is expelled, decreasing the robot's mass and allowing it to rise.

This system allows the robot to adjust its buoyancy without relying entirely on its thrusters.

### Mechanical Design Considerations

Important considerations included:

- Motor torque required to move the syringe plungers
- Alignment between the rack and pinion
- Friction within the syringe mechanism
- Available syringe volume
- Balanced placement of the two ballast syringes
- Space constraints inside the housing

We tested the ballast mechanism separately to verify that the motors and syringes could move as intended.

---

## Buoyancy and Housing Size

One of the biggest challenges was that our original housing was too buoyant.

Because the housing displaced a relatively large volume of water, the upward buoyant force was greater than the robot's weight, even when the ballast syringes were filled.

According to Archimedes' principle:

F_b = ρ_water × g × V_displaced

Where:

- F_b is the buoyant force
- ρ_water is the density of water
- g is gravitational acceleration
- V_displaced is the volume of water displaced by the robot

A larger housing displaces more water, increasing the buoyant force.

To address this, we began redesigning the housing with a smaller overall volume while still leaving enough room for the electronics, motors, and syringe mechanisms.

This required balancing internal space with the robot's ability to sink.

---

## Waterproof Housing Design

Waterproofing was another major engineering challenge because even a small leak could damage the electronics inside the robot.

Our original design used a cylindrical tube with end caps containing openings for external connections.

During manufacturing, we drilled the port holes before fully tightening the end caps.

When the caps were installed in their final positions, the holes no longer lined up correctly.

We attempted to correct the problem by redrilling the holes and applying sealing material, but these repairs did not produce a reliable watertight seal.

### Housing Redesign

Rather than continuing to repair the original end caps, we began redesigning the housing to incorporate the port holes directly into the 3D-printed components.

The redesign focuses on:

- Improving port alignment
- Reducing potential leak paths
- Making assembly more consistent
- Improving sealing around connections
- Reducing the overall housing volume
- Maintaining access to internal components

This approach allows us to address the original manufacturing problem through the design itself.

---

## CAD and 3D Printing

I used Fusion 360 to design and modify components for the submersible.

3D printing allowed us to prototype different housing and mounting designs and make changes as problems appeared during assembly.

Important design considerations included:

- Fit between the housing and end caps
- Port placement and alignment
- Mounting positions for motors and syringes
- Clearance for moving mechanisms
- Internal space for electronics and wiring
- Ease of assembly and maintenance

The project reinforced the importance of designing parts around how they will actually be manufactured and assembled.

---

## Testing and Troubleshooting

We tested the propellers and ballast system individually to check whether the mechanisms operated properly.

Both systems were able to move as intended during these initial tests.

However, the housing presented separate challenges related to waterproofing and buoyancy.

### Waterproofing Tests

To identify leaks, we are testing the empty housing by:

1. Assembling the housing without electronics
2. Submerging it in water
3. Pumping air into the housing
4. Watching for bubbles escaping through gaps or connections
5. Identifying leak locations and adjusting the design

This allows us to locate sealing problems without risking damage to the electronics.

### Buoyancy Testing

We also identified that the original housing displaced too much water for the ballast system to overcome.

Our redesign aims to reduce the housing size so the syringes can provide enough additional water mass to control the robot's depth.

Further testing will be needed to verify the redesigned housing's waterproofing and buoyancy performance.

---

## Engineering Lessons

This project taught me how closely connected mechanical design decisions can be.

Changing the housing size affects buoyancy, internal component placement, and assembly. Similarly, a small manufacturing mistake, such as drilling holes before final assembly, can create major waterproofing problems.

I also learned the importance of testing individual mechanisms before combining them into a complete system.

Most importantly, the project gave me experience identifying design failures, understanding their causes, and developing practical improvements through CAD, prototyping, and testing.
