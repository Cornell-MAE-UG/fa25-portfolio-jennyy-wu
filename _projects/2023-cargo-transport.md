---
layout: project
title: Cargo Transport System
permalink: /projects/cargo-transport/
description: Sikorsky STEM Challenge | High School
image: /assets/images/cargo_transport.jpg
---

<style>
.cargo-page {
  width: 85vw;
  max-width: 900px;
  margin-left: 50%;
  transform: translateX(-50%);
  padding: 20px 0 65px;
  box-sizing: border-box;
}

.cargo-page img {
  max-width: 100%;
  height: auto;
}

@media (max-width: 700px) {
  .cargo-page {
    width: calc(100% - 36px);
  }
}
</style>

<div class="cargo-page" markdown="1">

Our team built a semi-autonomous cargo transport system that could pick up a payload, move along a test frame, identify a destination by its roof color, and lower the payload there.

The mechanical design used a motor-driven hoist drum, rope, pulleys, and a magnetic hook. We used an Arduino Uno and color sensor to control the sequence: lower the hook to collect a payload, lift it, travel to the selected destination, and lower it again.

We compared several designs based on cost, durability, size, weight, efficiency, and ease of manufacturing. The pulley-based design scored highest in our trade study. In testing, we verified that the system could lift payloads from 0.5 to 2 pounds while meeting the challenge's 3-pound empty-weight limit and $100 development budget.

This was one of my first experiences seeing mechanical design, electronics, and code come together in a working system. Our team earned first place in the Sikorsky STEM Challenge.

</div>