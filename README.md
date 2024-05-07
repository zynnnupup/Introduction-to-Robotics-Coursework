# Introduction-to-Robotics-Coursework
## Introduction
This is a project about the Introduction to Robotics coursework。（Since the time is relatively short, the readme is not very standardized.）
We will show that the car uses the slam algorithm for positioning and mapping and the a* algorithm for path planning.
Currently we only show it in the simulation environment
## Introduction aux modules importants
### slam
There are many SLAM algorithms. Currently we use gmapping, which is a commonly used algorithm in ros. I will explore more algorithms and transplant them in the future.
The gmapping package provides laser-based SLAM (Simultaneous Localization and Mapping), as a ROS node called slam_gmapping. Using slam_gmapping, you can create a 2-D occupancy grid map (like a building floorplan) from laser and pose data collected by a mobile robot. --2024.4.22
### path planning
This time we are using A* algorithm, and we will gradually learn about new algorithms and transplant them in the future. --2024.4.22

imported the d*lite algorithm. --4.30
