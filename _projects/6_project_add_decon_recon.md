---
layout: page
title: Manned-Operated Indoor Decontamination System
description: Collaborative ground and aerial robot system for indoor decontamination tasks
img: assets/img/6.jpg
importance: 2
category: research projects
---

**Funded by:** Agency for Defense Development (ADD)<br>
**Duration:** 2024 – 2026<br>
**Location:** Unmanned System Research Group (USRG), KAIST EE

## Overview

This project develops a **collaborative multi-robot system** consisting of an Unmanned Ground Vehicle (UGV) and Unmanned Aerial Vehicle (UAV) to perform indoor decontamination tasks autonomously. The two robots work together to inspect, navigate, and treat contaminated indoor areas without human presence in hazardous zones.

## Research Challenges

- Coordinating heterogeneous robots (ground + air) in shared indoor spaces
- Autonomous navigation in semi-structured indoor environments
- Real-time task allocation and mission planning between UGV and UAV
- Precise manipulation and treatment of contaminated surfaces

## Technical Approach

- **Multi-robot Mission Planning** – Hierarchical task assignment between UGV and UAV agents
- **Indoor SLAM** – Simultaneous localization and mapping for both platforms
- **C++ ROS Packages** – Autonomous navigation using Dijkstra's algorithm for path planning
- **Robotic Manipulation** – The UGV performs physical decontamination operations
- **UAV Inspection** – The drone provides aerial perspective and assists with navigation/mapping
