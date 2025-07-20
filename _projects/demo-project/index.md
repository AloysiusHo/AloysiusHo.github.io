---
layout: post
title: Systems Engineering Project 1
description:  
  This project involves implementing a robotic system using the LIMO robot platform, ROS1 (Melodic) Navigation Stack, and RTAB-Map for real-time mapping. As part of the development, we designed a 1.33m x 1.5m Changi Airport-themed arena and programmed the robot to autonomously navigate not only within our own arena but also across arenas built by other teams. Using RTAB-Map, the robot was able to generate real-time maps of both familiar and unfamiliar environments to support autonomous navigation.
  
skills: 
  - Robot Operating System (ROS 1 Melodic)
  - C++ / Python Programming
  - -SLAM (Simultaneous Localization and Mapping)
  - Autonomous Navigation (using move_base, amcl, costmaps)
  - Linux/Ubuntu Development Environment
  - Sensor Integration (LIDAR, IMU, wheel encoders)
  - System Integration
main-image: /limo.png
---

---
# Design Challenge
The core challenge of this project was to build a robotic solution capable of reliable autonomous navigation across a variety of indoor arenas. To simulate real-world unpredictability, each team constructed their own unique layout, requiring our system to handle unfamiliar terrains and obstacles with no prior data. This highlighted the need for robust mapping, path planning, and localization strategies.



## Navigation Objective 
Our system was designed to move from its starting location to the center of a designated plot using the most efficient route. To achieve this, the robot needed to interpret sensor data, dynamically generate a map, and determine optimal paths.




## Thematic Arena: Canopy Park
Our arena design was inspired by Canopy Park at Changi Airport, incorporating both decorative features and physical obstacles to resemble a realistic airport setting. This thematic approach blended technical complexity with creative design.
{% include image-gallery.html images="Arena_2.jpg" height="400"%}



## Robot Platform: LIMO
For this project, we used the LIMO robot platform by AgileX Robotics. LIMO is a compact and versatile mobile robot equipped with multiple drive modes (Ackermann, omnidirectional, tracked, and differential)
{% include image-gallery.html images="limo.png" height="400"%} 



## Demonstration
This clip shows our LIMO robot navigating a themed arena using ROS1 and RTAB-Map. It performs real-time mapping and autonomous navigation, adapting to the environment and reaching the goal efficiently.  
If you would like to explore the source code for this project, you can visit our GitHub repository:  
[🔗 View Project Code on GitHub](https://github.com/YongJiee/Systems-Engineering-Project-1-Group-6.git)

{% include youtube-video.html id="QSk72anIw7c" autoplay = "true" width= "900px" %}  

<br>



