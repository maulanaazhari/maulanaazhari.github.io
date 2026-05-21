---
layout: page
title: Army Tiger DroneBot Challenge
description: Autonomous indoor reconnaissance drone through windows, Daejeon (2022)
img: assets/img/11.jpg
importance: 4
category: competitions
---

**Held by:** Republic of Korea Army Training and Doctrine Command (ROKA TRADOC)<br>
**Duration:** August 2022<br>
**Location:** Daejeon, South Korea

## Overview

The **5th Army Tiger DroneBot Mission Challenge** required developing a fully autonomous drone system that:

1. **Entered a building via a second-floor window** — requiring precise flight control and obstacle avoidance
2. **Located hidden objects in real time** inside the building
3. **Returned to its starting point** after completing the search

The operations can be done manually or autonomously, our system is operated autonomously beating the manually-controlled drones.

## Technical Approach

- **Autonomous Exploration Algorithm** – For systematic indoor exploration and mapping
- **Object Detection** – Real-time detection of hidden target objects
- **Synthetic Dataset Generation** – Custom synthetic training data to handle the indoor detection scenarios
- **Real-time Video Transmission** – Live video feed via WireGuard VPN, LTE module, Google Cloud, and ZMQ messaging for monitoring
- **LiDAR SLAM** – Accurate indoor localization and mapping

## Achievement

🥇 **1st Place** – 5th Army Tiger DroneBot Mission Challenge: Indoor Reconnaissance Drone (2022)

## Demo

<div class="embed-responsive embed-responsive-16by9 rounded z-depth-1">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/SXe_FJpxv94" allowfullscreen></iframe>
</div>
<p class="caption mt-2">Army Tiger DroneBot Challenge – Indoor Reconnaissance Demo</p>
