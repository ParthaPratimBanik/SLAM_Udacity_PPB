# Landmark Detection & Robot Tracking
A mini project on Landmark Detection &amp; Robot Tracking by implementing Simultaneous Localization and Mapping (SLAM) for 2D world.

## Project Overview:
---
In this project, you'll implement SLAM (Simultaneous Localization and Mapping) for a 2D world! You’ll combine what you know about robot sensor measurements and movement to create a map of an environment from only sensor and motion data gathered by a robot, over time. SLAM gives you a way to track the location of a robot in the world in real-time and identify the locations of landmarks such as buildings, trees, rocks, and other world features. This is an active area of research in the fields of robotics and autonomous systems.

Below is an example of a 2D robot world with landmarks (<span style="color:purple">purple x's</span>) and the robot (<span style="color:purple">a red 'o'</span>) located and found using only sensor and motion data collected by that robot. This is just one example for a 50x50 grid world; in your work you will likely generate a variety of these maps.

![Example of SLAM output (estimated final robot pose and landmark locations).](images/robot_world.png)
<p style="text-align: center;">Example of SLAM output (estimated final robot pose and landmark locations).</p>


## Project Instructions
---
The project will be broken up into 3 Python notebooks; the first 2 are for exploration of provided code, and a review of SLAM architectures and notebook 3 is on the implementation of SLAM with [robot_class_.py](/robot_class.py):

Notebook 1 : [Robot Moving and Sensing](/1_Robot_Moving_and_Sensing.ipynb)

Notebook 2 : [Omega and Xi, Constraints](/2_Omega_and-Xi_Constraints.ipynb)

Notebook 3 : [Landmark Detection and Tracking](/3_Landmark_Detection_and_Tracking.ipynb)


You can also complete this project in your own local repository by using this [GitHub repository](https://github.com/udacity/P3_Implement_SLAM).