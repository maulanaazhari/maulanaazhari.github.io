---
layout: about
title: about
permalink: /
# subtitle: >
#   PhD Candidate · <a href="https://unmanned.kaist.ac.kr/" target="_blank">Unmanned System Research Group (USRG)</a> · <br> <a href="https://ee.kaist.ac.kr/" target="_blank">School of Electrical Engineering, Korea Advanced Institute of Science and Technology (KAIST)</a>

profile:
  align: left
  image: pas_foto_ari.jpg
  image_circular: false # crops the image to make it circular
  # width: 100px
  # more_info: >
  #   <p>mbazhari@kaist.ac.kr</p>
  #   <p>maulanabisyira@gmail.com</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
  scrollable: true
  limit: 3
---

<style>
  .profile {
    max-width: 150px !important;
  }
  
  .profile img {
    max-width: 100% !important;
    width: auto !important;
  }
</style>

I am a PhD Candidate in Electrical Engineering at [Korea Advanced Institute of Science and Technology (KAIST)](https://www.kaist.ac.kr/), where I work at the [Unmanned System Research Group (USRG)](https://unmanned.kaist.ac.kr/) under the supervision of [Prof. David Hyunchul Shim](https://scholar.google.com/citations?user=-CKm5DEAAAAJ&hl=en&oi=ao). My research focuses on **visual and inertial state estimation** for **autonomous drones** — spanning learning-based visual odometry/SLAM, high-speed state estimation for autonomous drone racing, and real-world autonomous systems for maritime security and exploration. I have defended my PhD thesis, with title: _Specialized and Generalized Visual and Inertial State Estimation: From Autonomous Drone Racing to Diverse Environments_.

Now open for opportunities! email: maulanabisyira(at)gmail(dot)com

<!-- I am passionate about building drones that can perceive, reason, and act autonomously in challenging real-world environments. My work ranges from high-speed autonomous drone racing to maritime search-and-rescue operations in GPS-denied environments.

**Research interests:** Visual(-Inertial) Odometry/SLAM · LiDAR SLAM · Autonomous Exploration · Object Detection & Tracking · Model Predictive Control · Drone Racing -->

<div style="clear: both;"></div>

### Learning-Based Visual Odometry/SLAM

<div class="row">
  <div class="col-12 col-md-6 mt-3">
    {% include youtube.liquid id="fRehsAx6uxU" title="Vision-based Flights Inside a Dark Tunnel (No GPS, No LiDAR)" %}
    <p class="caption mt-2 text-center">Vision-based Flights Inside a Dark Tunnel (No GPS, No LiDAR)</p>
  </div>
  <div class="col-12 col-md-6 mt-3">
    {% include youtube.liquid id="VKhkDUh09_k" title="Vision-Based Autonomous Flights – Obstacle Avoidance" %}
    <p class="caption mt-2 text-center">Vision-Based Autonomous Flights – Obstacle Avoidance</p>
  </div>
  <div class="col-12 col-md-6 mt-3">
    {% include youtube.liquid id="Irt8IjYCX_Y" title="Vision-based Autonomous Flights – Indoor and Outdoor" %}
    <p class="caption mt-2 text-center">Vision-based Autonomous Flights – Indoor and Outdoor</p>
  </div>
  <div class="col-12 col-md-6 mt-3">
    {% include youtube.liquid id="NwDckPrDR5o" title="DINO-VO (IEEE RA-L 2025)" %}
    <p class="caption mt-2 text-center">DINO-VO (IEEE RA-L 2025)</p>
  </div>
</div>

<p class="mt-0 mb-5">Robust camera-based localization that leverages learned features and visual foundation models, enabling GPS-free and LiDAR-free flight in challenging environments such as dark tunnels. My latest work, LiΣ-SLAM, is able to be deployed on Orin NX computer in real-time. My previous work, DINO-VO, integrated the robust, generalizable features of a visual foundation model in a feature-based visual odometry pipeline.<br>Related: LiΣ-SLAM (in preparation), <a href="https://ieeexplore.ieee.org/document/11091393" target="_blank">DINO-VO (IEEE RA-L 2025, presented at IEEE ICRA 2026)</a>.</p>

### State-Estimation for Autonomous Drone Racing

<div class="row">
  <div class="col-12 col-md-6 mt-3">
    {% include youtube.liquid id="QkZY0So3myw" title="VeloBins for Aerial Inertial Odometry" %}
    <p class="caption mt-2 text-center">VeloBins for Aerial Inertial Odometry</p>
  </div>
  <div class="col-12 col-md-6 mt-3">
    {% include youtube.liquid id="px_rxrNlEyc" title="Drone Racing Event Supercut (2026 Nature Conferences: Autonomous Robotics)" %}
    <p class="caption mt-2 text-center">Drone Racing Event, 2026 Nature Conferences: Autonomous Robotics</p>
  </div>
  <div class="col-12 col-md-6 mt-3">
    {% include youtube.liquid id="x_IDrf6j0qs" title="Team KAIST at the 2026 A2RL Drone Championship AI Speed Race" %}
    <p class="caption mt-2 text-center">Team KAIST at the 2026 A2RL Drone Championship AI Speed Race</p>
  </div>
  <div class="col-12 col-md-6 mt-3">
    {% include youtube.liquid id="omncgCLqqWA" title="A2RL Autonomous Drone Racing Season 1 (April, 2025)" %}
    <p class="caption mt-2 text-center">A2RL Autonomous Drone Racing Season 1 (April, 2025)</p>
  </div>
</div>

<p class="mt-0 mb-5">High-speed visual-inertial and learning-based inertial state estimation using only a single monocular RGB camera and an IMU, developed for the A2RL Autonomous Drone Championship. My work spans a tightly-coupled filter-based monocular VIO with graph-based evaluation, drift correction combined with perception-aware planning, and VeloBins, which learns velocity and its uncertainty directly from inertial data. <br>Related: <a href="https://onlinelibrary.wiley.com/doi/10.1002/rob.70371" target="_blank">Drift-Corrected VIO (JFR 2026)</a>, <a href="https://arxiv.org/abs/2603.02742" target="_blank">ADR-VINS (IEEE IROS 2026)</a>, <a href="https://arxiv.org/abs/2608.29720" target="_blank">VeloBins (under revision at IEEE RA-L)</a>.</p>

### Maritime Security (Mohamed bin Zayed International Robotics Challenge)

<div class="row">
  <div class="col-12 mt-3">
    {% include youtube.liquid id="Ya1pfWYRMrc" title="MBZIRC Team Profile – Team KAIST" %}
    <p class="caption mt-2 text-center">MBZIRC Team Profile – Team KAIST</p>
  </div>
  <div class="col-12 col-md-6 mt-3">
    {% include youtube.liquid id="SOPcTh2B-64" title="SPIBOT: A Drone-Tethered Mobile Gripper for Aerial Grasping (ICRA 2025)" %}
    <p class="caption mt-2 text-center">SPIBOT: A Drone-Tethered Mobile Gripper for Aerial Grasping (ICRA 2025)</p>
  </div>
  <div class="col-12 col-md-6 mt-3">
    {% include youtube.liquid id="bOa8pcnZ7cU" title="UAV-USV Relative Localization at MBZIRC" %}
    <p class="caption mt-2 text-center">UAV-USV Relative Localization at MBZIRC</p>
  </div>
</div>

<p class="mt-0 mb-5">A collaborative UAV–USV system to detect illegal vessels and retrieve stolen objects in a GPS-denied marine environment — 2nd place at MBZIRC 2024. The system relies on AprilTag-based and optical-flow localization, I also developed the mission planner, control, and real-time object detection and tracking.<br>Related: <a href="https://ieeexplore.ieee.org/document/11128830" target="_blank">SPIBOT (IEEE ICRA 2025)</a>.</p>

### Autonomous Drone Exploration

<div class="row">
  <div class="col-12 col-md-6 mt-3">
    {% include youtube.liquid id="SXe_FJpxv94" title="Autonomous Exploration in Unknown Environments (Army Tiger DroneBot Challenge)" %}
    <p class="caption mt-2 text-center">Autonomous Exploration in Unknown Environments (Army Tiger DroneBot Challenge)</p>
  </div>
  <div class="col-12 col-md-6 mt-3">
    {% include youtube.liquid id="h_PsFVhh-As" title="Autonomous Exploration with AI-Powered Artifact Detection (ADD Battlefield Drone)" %}
    <p class="caption mt-2 text-center">Autonomous Exploration with AI-Powered Artifact Detection (ADD Battlefield Drone)</p>
  </div>
</div>

<p class="mt-0 mb-5">Fully autonomous indoor reconnaissance with LiDAR-inertial odometry, exploration, and onboard object detection — 1st place at the Army Tiger DroneBot Challenge and Top 2 at the ADD Battlefield Drone competition. The drones enter unknown, GPS-denied buildings, explore them, locate hidden targets in real time, and return to the start using only onboard computation. <br>Related: <a href="https://onlinelibrary.wiley.com/doi/10.1002/rob.22284" target="_blank">Adaptive LIO with Practical UAV Exploration (JFR 2024)</a>.</p>

## Publications (selected)

<div class="publications">
  {% bibliography --group_by none --query @*[selected=true]* %}
</div>

## Awards

<div class="awards mt-4">
  <ul class="list-unstyled">
    <li class="mb-2"><strong>2026</strong> — KAIST Challenge Award, KAIST's 55th Anniversary</li>
    <li class="mb-2"><strong>2026</strong> — 4th Place of Speed Race, A2RL Drone Championship (Abu Dhabi, UAE)</li>
    <li class="mb-2"><strong>2025</strong> — 3rd Place of AI Grand Challenge, A2RL X DCL Drone Championship (Abu Dhabi, UAE)</li>
    <li class="mb-2"><strong>2025</strong> — 2nd Place of AI Multi-Drone Race, A2RL X DCL Drone Championship (Abu Dhabi, UAE)</li>
    <li class="mb-2"><strong>2025</strong> — 2nd Place of AI Drag Race, A2RL X DCL Drone Championship (Abu Dhabi, UAE)</li>
    <li class="mb-2"><strong>2025</strong> — KAIST Challenge Award, KAIST's 54th Anniversary</li>
    <li class="mb-2"><strong>2024</strong> — 2nd Place, 3rd Mohamed Bin Zayed Robotics Challenge (MBZIRC) (Abu Dhabi, UAE)</li>
    <li class="mb-2"><strong>2022</strong> — Top 2 Teams, ADD Autonomous Drone for Battlefield Environments (Daejeon, South Korea)</li>
    <li class="mb-2"><strong>2022</strong> — 1st Place, 5th Army Tiger DroneBot Challenge (Daejeon, South Korea)</li>
    <li class="mb-2"><strong>2019</strong> — Finalist of EDF Rocket Control System, KOMURINDO-KOMBAT (Garut, Indonesia)</li>
    <li class="mb-2"><strong>2018</strong> — Finalist, 31st National Student Scientific Week (PIMNAS) (Yogyakarta, Indonesia)</li>
    <!-- <li class="mb-2"><strong>2016</strong> — BIDIKMISI Scholarship (Ministry of Research, Technology, and Higher Education)</li> -->
    <li class="mb-2"><strong>2015</strong> — 1st Place of Quick and Smart, ESA FEST (Serang, Indonesia)</li>
  </ul>
</div>

{% comment %} The sections below are read from \_data/cv.yml (same data as the CV page). {% endcomment %}
{% assign cv_sections = site.data.cv.cv.sections %}

## Skills

<div class="mt-4">
  <ul class="list-unstyled">
    {% for skill in cv_sections.Skills %}
      <li class="mb-2"><i class="{{ skill.icon }} mr-1"></i> <strong>{{ skill.name }}</strong> — {{ skill.keywords }}</li>
    {% endfor %}
  </ul>
</div>

## Languages

<div class="mt-4">
  <ul class="list-unstyled">
    {% for language in cv_sections.Languages %}
      <li class="mb-2"><strong>{{ language.name }}</strong> — {{ language.summary }}</li>
    {% endfor %}
  </ul>
</div>

## Service and Activities

<div class="mt-4">
  <ul class="list-unstyled">
    {% for item in cv_sections["Service and Activities"] %}
      <li class="mb-2"><strong>{{ item.label }}</strong> — {{ item.details }}</li>
    {% endfor %}
  </ul>
</div>
