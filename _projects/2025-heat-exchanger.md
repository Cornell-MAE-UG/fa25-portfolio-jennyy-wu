---
layout: project
title: Heat Exchanger System Analysis
description: Thermodynamics Coursework Project
technologies: [Thermodynamics, Energy Balance, Heat Transfer]
image: /assets/images/heat-exchanger.jpg
---

This project examines a compact water-to-water heat exchanger studied as part of an
undergraduate thermodynamics laboratory. The objective of the experiment was to analyze
how thermal energy is transferred between two fluid streams and how system performance
changes under different operating conditions.

The experiment focused on steady-flow analysis, conservation laws, and entropy generation
in a real engineering system.

---

## System Description

The experimental setup consisted of a plate heat exchanger connected to two independent
water circulation loops. One loop supplied hot water from a reservoir heated using an
immersion heater, while the second loop supplied cold water from an insulated reservoir.
Each loop was driven by a small pump, and inlet and outlet temperatures were measured
using thermometers and a thermocouple.

Thermal energy was exchanged between the two water streams through the heat exchanger
walls without direct mixing of the fluids.


---

## Thermodynamic Modeling

The heat exchanger was modeled as a steady-flow control volume. The following assumptions
were made:

- Steady-state operation  
- Incompressible liquid water  
- Negligible kinetic and potential energy changes  
- No shaft work within the heat exchanger  
- Heat transfer occurs only between the two fluid streams  

Under these assumptions, separate mass balances apply to each fluid stream, while energy
is conserved across the control volume.

---

## Governing Balances

## Governing Balances

To analyze the heat exchanger under steady operating conditions, the system is modeled as a steady-flow control volume.

Because the system operates at steady state, mass does not accumulate within the exchanger. Therefore, for each fluid stream:

\[
\dot{m}_{in} = \dot{m}_{out}
\]

Applying the steady-flow energy equation to the control volume yields:

\[
\dot{m}_h c_p (T_{h,out} - T_{h,in}) +
\dot{m}_c c_p (T_{c,out} - T_{c,in}) = 0
\]

This relationship expresses conservation of energy: the thermal energy lost by the hot stream is equal to the energy gained by the cold stream.

To assess irreversibilities within the exchanger, the entropy balance is applied:

\[
\dot{S}_{gen} =
\dot{m}_h (s_{h,out} - s_{h,in}) +
\dot{m}_c (s_{c,out} - s_{c,in}) \ge 0
\]

The positive entropy generation term reflects the irreversible nature of heat transfer across a finite temperature difference.

---

## Effect of Operating Conditions on Performance

#### Parallel Flow vs Counterflow Operation

The heat exchanger was operated in both parallel-flow and counterflow configurations.
In parallel flow, the hot and cold water streams entered the heat exchanger from the same
end and flowed in the same direction. In counterflow operation, the streams entered from
opposite ends and flowed in opposite directions.

During parallel-flow operation, a large temperature difference existed near the inlet,
but the temperature difference decreased rapidly along the length of the exchanger.
This resulted in lower overall heat transfer effectiveness.

In contrast, counterflow operation maintained a more uniform temperature difference
between the two streams along the exchanger length. As a result, the cold outlet
temperature could approach the hot inlet temperature more closely, leading to improved
thermal performance. This behavior is consistent with thermodynamic theory and explains
why counterflow heat exchangers are commonly preferred in engineering applications.

Changes in flow rate also affect system performance. Increasing the flow rate of one
stream increases the rate of heat transfer but may reduce the temperature change of that
stream due to decreased residence time.

---

## Engineering Relevance

Heat exchangers are widely used in applications such as power generation, HVAC systems,
automotive cooling, and chemical processing. Understanding the thermodynamic behavior of
these systems is essential for designing efficient energy systems and minimizing
irreversibilities in real-world engineering applications.