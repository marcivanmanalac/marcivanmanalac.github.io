---
layout: project
type: project
image: img/scada/scada-cat.png
title: "SCADA Lab"
date: 2021
published: true
labels:
  - Linux
  - Circuits
  - Systems
  - Network Design
  - Raspberry Pi
  - Programmable Logic Circuits
summary: "A senior design project developing a SCADA Network with legacy industrial components."
---

### Summary
<img class="text-center p-4" width="400px" height="400px" src="https://media.giphy.com/media/mxO1AalLCm542j8tMo/giphy.gif" alt="Power Utility System" style="float:right;">
     SCADA Lab was a two-semester long capstone(currently ongoing) that allowed EE,ICS, & CENG students to experience designing and building a system in a faux-engineering company manner. The term SCADA stands for Supervisory Control and Data Acquisistion. It is any closed-loop self regulating system that utilizes sensors and actuators to interface with the real world. These systems can be found in major infrastructure such as traffic systems, utilities, railways, airports and more.

     Our motivation for SCADA comes from notable cybersecurity attacks.
<ol>
     <li>2010 Stuxnet in Iran</li>
     <li>2013 Target HVAC System Attack</li>
     <li>2015 Black Energy Crisi Ukraine</li>
     <li>2021 Colonial Pipeline</li>
</ol>



## Our Design
Our system was to emulate a network of a power utility company such as HECO. On one end we have actuators such as power transmission line protection and high power relays. These devices each operate using a private version of linux and can be accessed via ethernet and serial. The devices are are connected via a wireless gateway and controlled and monitored by a user in a private network through yagi antennas.

<div class="zoom-within-container">
     <div class="text-center p-4">
     <img width="200px" height="200px" 
          src="../img/scada/sel-setup.jpg" 
          class="img-thumbnail" >
     <img width="200px" height="200px"
          src="../img/scada/sel-stat-leds.JPG" 
          class="img-thumbnail" >
     <img width="200px" height="200px"
          src="../img/scada/SEL-3505-ethernet-port.jpg" 
          class="img-thumbnail" >
     <img width="200px" height="200px"
          src="../img/scada/PLC.jpg" 
          class="img-thumbnail" >
     </div>
</div>

## The future of the Capstone
<img width="200px" class="rounded float-start pe-4" src="https://media.giphy.com/media/077i6AULCXc0FKTj9s/giphy.gif" style="float:right;">
In future iterations of the system, the team will be looking to implement different open source software defined networks for additional network security. They start to experiment on different machine learning algorithms and restructure the network design to follow the National Institute of Standards and Technologies Zero Trust Architecture. They will also be mounting the system on top of Holmes Hall and create a wireless network with the ICS building.


Not only was it a valuable learning experience, but I was able to be a part of multiple facets of the process. I designed and pitched my own SCADA system to the team. I was able to contact real support teams from Schweitzer Engineering Labs for assistance in troubleshooting components. I was introduced to some principles of computer networking and the use cases in industrial technologies. I experienced team bulding and communicating to solve problems with fellow students with different STEM backgrounds. We also participated in a end of semester Defense Innovation Mixer where we presented our design project and viewed different projects related to solving real-world cybersecurity problems.
<div class="text-center p-4">
     <img width="600px" class="img-fluid" src="../img/scada/h4d.jpg" style="float:center;">
     <p><a href="../reports/scada_report_fall21.pdf">SCADA FALL 21 Report</a></p>
</div>




