---
layout: page
title: A2RL Autonomous Drone Championship
description: High-speed drone racing using only monocular camera + IMU, Abu Dhabi (2025–2026)
img: assets/img/7.jpg
importance: 1
category: competitions
---

**Held by:** [ASPIRE](https://www.aspireuae.ae/) – Abu Dhabi Autonomous Racing League, United Arab Emirates<br>
**Duration:** September 2024 – Present<br>
**Location:** Abu Dhabi, United Arab Emirates

## Overview

The [A2RL Autonomous Drone Championship](https://a2rl.io/autonomous-drone-race) is a cutting-edge autonomous drone racing competition organized by [ASPIRE](https://www.aspireuae.ae/) in Abu Dhabi. Our team develops algorithms that enable drones to race at high speed by relying **exclusively on a single monocular RGB camera and an IMU sensor** — no GPS, no LiDAR, no depth cameras.

## Technical Approach

The system must handle real-time perception, navigation, and control at racing speeds, requiring tight integration of multiple robotics stacks:

- **Visual-Inertial Localization** – Tightly-coupled monocular VIO for accurate and robust state estimation during high-G maneuvers
- **Gate Detection** – Real-time detection of race gates from monocular images
- **Model Predictive Control (MPC)** – Aggressive yet safe trajectory tracking
- **Optimal Trajectory Planning** – Minimum-time path planning through gate sequences

## Achievements

- 🥉 **3rd Place** – AI Grand Challenge, A2RL × DCL Drone Championship (2025)
- 🥈 **2nd Place** – AI Multi-Drone Race, A2RL × DCL Drone Championship (2025)
- 🥈 **2nd Place** – AI Drag Race, A2RL × DCL Drone Championship (2025)
- 🏅 **4th Place** – Speed Race, A2RL Drone Championship (2026)

## Demo

<div class="mt-3">
  <div class="embed-responsive embed-responsive-16by9 rounded z-depth-1">
    <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/x_IDrf6j0qs" allowfullscreen></iframe>
  </div>
  <p class="caption mt-2">A2RL Drone Racing Season 2 (January, 2026)</p>
</div>

<div class="mt-3">
  <div class="embed-responsive embed-responsive-16by9 rounded z-depth-1">
    <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/omncgCLqqWA" allowfullscreen></iframe>
  </div>
  <p class="caption mt-2">A2RL Drone Racing Season 1 (April, 2025)</p>
</div>

## Links

- competition website: [a2rl.io/autonomous-drone-race](https://a2rl.io/autonomous-drone-race)
- paper 1: [Robust Tightly-Coupled Filter-Based Monocular Visual-Inertial State Estimation and Graph-Based Evaluation for Autonomous Drone Racing](https://arxiv.org/pdf/2603.02742)
- paper 2: [Drift-Corrected Monocular VIO and Perception-Aware Planning for Autonomous Drone Racing](https://arxiv.org/pdf/2512.20475)
