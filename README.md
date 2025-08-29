This repository contains the implemetation of our final year project
"Optimal gait pattern generation for a weight carrying hexapod robot using reinforcement learning."
The work explores how the reinforcement learning algorith can be used to generate an optimal gait for a weight carrying hexapod robot.
Legged robots are good in stability and adaptability than the wheeled robots.
Among legged robots hexapods are good in stability and energy efficiency due to their six legged structure. 
Due to these features hexapods can be used in rough terrains, underwater searches, search and rescue missions.
Obtaining an optimal gait for the robot locamotion plays a major role in effieciecy and stability
We completed this project in followinfg successful steps
  1. Built the robot from scratch in Mujoco, defined by an XML file contains body, actuators, contacts, joint limits and payload.
  2. Import the robot model using Brax framework in google colabs.
  3. Robot consists of six legs and a centralized body.
  4. Train the model using reinforcement learning.
  5. Idetify and incorporate reinforcement learning algorith
  6. Obtain the optimal gait
