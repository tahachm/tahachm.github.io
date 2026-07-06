---
layout: page
title: Terrestrial–Non-Terrestrial 5G Testbed
description: Cross-layer testbed design for integrating terrestrial and non-terrestrial 5G
img: assets/img/5g.png
importance: 2
category: research
---

As a Graduate Research Assistant at the University of Waterloo, I work on integrating **terrestrial and non-terrestrial (NTN) 5G access** within a cross-functional CS/ECE team.

I abstracted a testbed design that uses cross-layer information sharing to drive optimizations across **scheduling, beamforming, and transport** and led key technical decisions (integration between hardware and software stacks). My testbed diagram became the reference artifact for explaining our approach in stakeholder meetings.

I mapped the testbed proposals onto open-source 5G stacks — [Open5GS](https://open5gs.org/), [srsRAN](https://www.srslte.com/), and [OpenAirInterface](https://openairinterface.org/). I translated the hardware team's non-terrestrial channel models to OpenArInterface's rfisim module in C, and am currently running experiments to prove bottlenecks in traditional scheduling algortihms in the long-delay scenario of NTN access.