---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.Sc. Aerospace Engineering, Technische Universität München, 2024 – present  
* B.Sc. Mechanical Engineering, Middle East Technical University, 2017 – 2023  

Work experience
======
* Opto-Mechatronics Engineer, TÜBİTAK SAGE, Ankara, Turkey (15/07/2023 – 01/03/2024)  
  * 3D design and technical drawings of opto-mechatronic components.  
  * System identification of missile seeker head systems.  
  * Hardware testing and validation of integrated systems.  

* Working Student, Turkish Aerospace Industries, Ankara, Turkey (15/11/2022 – 30/05/2023)  
  * Helicopter blade design and analysis.  
  * Blade test analysis and support for manufacturing activities.  

Projects
======
* F1TENTH Autonomous Driving Project (24/12/2025 – present)  
  * Developed a ROS 2–based reinforcement learning environment for the F1TENTH autonomous racing simulator.  
  * Implemented time-optimal lap completion with collision-based resets and a custom reward function.  
  * Trained the AI model in a Dockerized ROS 2 simulation environment and deployed it to a physical vehicle.  

* Antenna Tracker for Long Distance UAV Communication (Semester Thesis, 01/05/2025 – 01/11/2025)  
  * Designed, modelled, and prototyped a 2-DOF (pitch and heading) antenna tracker for long-range UAV communication.  
  * Implemented a real-time control system using ROS2 on Raspberry Pi and received sensor data from Pixhawk via MAVLink.  
  * Controlled stepper motors using Python and created the mechanical design in Onshape for 3D printing.  

* Phantum (Student Initiative, 01/01/2026 – present)  
  * Hardware-in-the-loop (HIL) simulation with Pixhawk 6C hardware using MATLAB/Simulink and the PX4 support package.  

* Autonomous Driving Project (Introduction to ROS course final project, 01/07/2025 – 01/08/2025)  
  * Implemented autonomous navigation including trajectory and path generation, state machines, and control.  

Skills
======
* Flight simulations, flight mechanics, flight control  
* MATLAB, Simulink, ROS / ROS 2  
* Python, C++, Git (version control)  
* Raspberry Pi, Arduino  
* Siemens NX, Onshape, 3D printing (Bambu Studio)  

Languages
======
* Turkish (mother tongue)  
* English (C1)  
* German (A2)  

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
