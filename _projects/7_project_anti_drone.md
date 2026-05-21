---
layout: page
title: Anti-Drone System with Jammer
description: Autonomous detection and jamming system for counter-drone operations
img: assets/img/8.jpg
importance: 3
category: lab projects
---

**Funded by:** KAIST / External Research Grant<br>
**Duration:** December 2022 – Present<br>
**Location:** Unmanned System Research Group (USRG), KAIST EE

## Overview

This project focuses on developing an **anti-drone system** that combines autonomous detection, tracking, and RF jamming to neutralize unauthorized drones in protected airspace. The system operates without human-in-the-loop decisions for tactical scenarios.

## Research Challenges

- Reliable detection and classification of small drones at range
- Tracking fast-moving aerial targets in real time
- Directing an RF jammer with sufficient accuracy to disrupt drone communication links
- Minimizing false positives (birds, authorized aircraft) while maintaining sensitivity

## Technical Approach

- **C++ ROS Packages** – Custom ROS nodes for system integration, sensor processing, and robot control
- **Autonomous Navigation** – Dijkstra's algorithm-based path planning for mobile jammer positioning
- **Robotic Manipulation** – Precise jammer directional control to target detected drones
- **Object Detection & Tracking** – Real-time aerial target detection and tracking pipeline
- **RF Jamming Integration** – Coordinated RF disruption module for drone countermeasures
