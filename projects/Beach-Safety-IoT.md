---
layout: project
type: project
image: img/watchtower/lifeguard-tower.jpg
title: "WatchTower Beach Safety IoT"
date: 2022
published: true
labels:
  - NodeRed
  - Single Board Computers
  - Sensors
  - IoT
summary: "An IoT device for displaying Beach Conditions"
---

## WatchTower
This project was conducted during the Spring 2022 Semester at the University of Hawaii at Manoa in the Cyber-Physial Systems and IoT course. My team members and I were tasked with developing an IoT device that utilized a web API along with a raspberry pi and sensors. Our solution focused was an outdoor warning system for the many unattended beaches on Hawaii. 

<div class="text-center p-4">
<video width="640" height="480" controls>
  <source src="../img/watchtower/watchtower-vid.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
</div>

## Design
Our four man team was split into two sub-teams. One focused on the Beach Safety API and the other, which I was on, focused on the physical device build. We utilized the browser-based flow editor, NodeRed, to receive data from the public API and it's specific information for beaches on different facing beaches on the island of O'ahu. The information would then be sent into a pi node which actuates a servo and LED that displays beach hazard conditions in real time. 

<div class="text-center p-4">
<img class="img-thumbnail" src="../img/watchtower/cloud-IoT.png" width="800px">
<img class="img-thumbnail" src="../img/watchtower/watchtower-hardware.png" width="800px">
</div>

<div>
<p><a href="../reports/WatchTower-IoT-Project.pdf">Final Report</a></p>
</div>
