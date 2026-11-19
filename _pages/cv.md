---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Robotics researcher at **Julius-Maximilians-Universität Würzburg (JMU)** and co-founder of **[Harsher](https://www.harsher.de)**. My research focuses on robust localization and mapping, Doppler-aided SLAM, 4D radar, and multimodal perception for autonomous systems in harsh and dynamic environments.

Education
======
* **Ph.D. in Robotics**, Julius-Maximilians-Universität Würzburg, 2026
  * Defended on **July 31, 2026**, with **summa cum laude**
  * Dissertation: *Doppler-Aided Localization and Mapping for Autonomous Systems*
  * Supervisors: Prof. Dr. Andreas Nüchter and Prof. Dr. Stefan May
  * [JMU announcement](https://www.informatik.uni-wuerzburg.de/en/robotics/news/detail/news/dong-wang-successfully-completes-his-phd/)
* M.Sc. in Robotics, Friedrich‑Alexander‑Universität Erlangen‑Nürnberg, 2020
* B.Eng. in Mechatronics, Nuremberg Institute of Technology, 2017
* B.Sc. in Mechatronics, Tongji University, 2017

Work experience
======
* **Co-founder, [Harsher](https://www.harsher.de)**
  * Radar-first perception, localization, and safety systems for heavy machinery and outdoor service robots in harsh environments

* Spring 2024 – Present: Research Associate
  * Julius‑Maximilians‑University Würzburg
  * Research on 3D SLAM based on sensor fusion for mobile robots
  * Supervisor: Prof. Dr. Andreas Nüchter

* Dec 2020 – Aug 2024: Software Developer
  * Evocortex GmbH
  * Agile ROS/Linux development
  * Digital‑twin infrastructure for next‑generation mobile robots
  * Sensor fusion for AMRs and UAVs (LiDAR, camera, ultrasound, radar)
  * Supervisor: Daniel Ammon

* May 2021 – Dec 2023: Research Assistant
  * Hybrid sensor‑fusion research for mobile robots
  * AutonOhm RoboCup 2021–22 Rescue; 2023 Industrial @ Work (software lead)
  * Supervisor: Prof. Dr. Stefan May

* Feb 2020 – Oct 2020: Research Assistant
  * Friedrich‑Alexander‑Universität Erlangen‑Nürnberg (FAPS)
  * 3‑D route‑planning framework for multi‑UAV systems (Master’s thesis)
  * Supervisor: Prof. Dr. Jörg Franke

Research funding and awards
======
* **DFG research funding**, announced November 2026
  * Project: *Reliability-Aware Multimodal SLAM for Long-Term Autonomy in Harsh Environments*
  * Approximately **€230,000** for a two-year project starting **January 1, 2027**
  * Jointly applied for with Technische Hochschule Nürnberg Georg Simon Ohm
  * [University press release](https://idw-online.de/de/news880998)
* **BayWISS Prize 2025**, October 2025
  * Awarded for outstanding or pioneering research achievements
  * [Award announcement](https://www.baywiss.de/news-und-termine/news-detail/baywiss-preis-2025-fuer-eine-herausragende-oder-zukunftsweisende-forschungsleistung-im-jeweiligen-wissenschaftsbereich)

Skills
======
* Programming
  * C/C++
  * Python
  * Java
* Tools & Frameworks
  * ROS1/2, Docker, Linux
  * PCL, OpenCV, MATLAB
  * Git, Azure DevOps
* Languages
  * Chinese (native)
  * English (fluent)
  * German (C1)

Publications
======
  {% assign publications = site.publications | sort: "date" | reverse %}
  <ul>{% for post in publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching and supervision
======
* Supervision of undergraduate thesis projects at Julius-Maximilians-Universität Würzburg
  
Service and leadership
======
* AutonOhm software team leader, RoboCup competitions (2021–2025)
* Mentor for Chinese students coming to study in Germany
* Reviewer for IEEE TR-O, RA‑L, CASE, IROS (since 2023)
