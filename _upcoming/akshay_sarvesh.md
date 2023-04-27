---
layout: talk
type: "Talk"
date: 2023-05-03
name: "Akshay Sarvesh"
teaser: "Algorithms for Autonomous Navigation of Robots in Unstructured Terrain"
link: "/upcoming/akshay_sarvesh"
register: "https://us02web.zoom.us/meeting/register/tZIlceyorDsuHd0jANlEpTQRORqTo93aDTLD"
---

### Speaker 
Akshay Sarvesh is a PhD Candidate and a Researcher in the Electrical and Computer Engineering Department at Texas A&M University, working in the domain of Robotics. Over the course of his research so far, he has developed algorithms in the domain of Motion Planning, Path Planning and Dynamic Control of Robots in Unstructured Terrain using RL based techniques and Classical techniques. He is interested in the idea of different types of Robots specializing in different tasks collaborating together and co-operating with each other to fulfill a more difficult task. He is interested in collaborating with different researchers and is looking forward to transitioning from his PhD to a Research based role.

Speaker Links: [Personal Website](https://people.tamu.edu/~akshays25/) - [Google Scholar](https://scholar.google.com/citations?user=8P7o-QUAAAAJ) - [LinkedIn](https://www.linkedin.com/in/akshaysarvesh/)

### Abstract 
Path Planners that reshape a global path locally in response to sensor-based observations of obstacles in the environment are presented.

(i) Reshaping Local Path Planner (RLP). Two fundamental concepts enable the resultant algorithm (a) a path-following synthetic vehicle whose steering actions are non-myopically optimized to result in a smooth traversible path that meets path curvature constraints, and (b) a path aware turning moment-field that enables obstacle avoidance while eluding the typical local-minimum-induced stagnation associated with potential field methods. The use of the combination of the two concepts results in a reduced action space over which optimization needs to be performed towards minimizing the path deviation subject to obstacle avoidance, and thus results in an efficient algorithm that can be implemented online.

(ii)Reshaping Viscoelastic-String Path-Planner (RVP) models the path to be a viscoelastic string with shape preserving tendencies, approximated by a connected series of Springs, Masses, and Dampers. The resultant path is then reshaped according to the forces emanating from the obstacles until an equilibrium is reached. The reshaped path remains close in shape to the original path because of Anchor Points that connect to the discrete masses through springs. The final path is the resultant equilibrium configuration of the Spring-Mass-Damper network. Two key concepts enable RVP (i) Virtual Obstacle Forces that push the Spring-Mass-Damper system away from the original path and (ii) Anchor points in conjunction with the Spring-Mass-Damper network that attempts to retain the path shape.

The algorithms are demonstrated in simulations and in field experiments, performing real time local path planning and obstacle avoidance on two different vehicle platforms (an ackerman steering vehicle two-axled vehicle, and a differential-steering 4-axled vehicle) in an unstructured off-road terrain.

Relevant [video](https://www.youtube.com/watch?v=Zq5yOXD48bg).

### Papers: 
- [Reshaping Local Path Planner (RLP)](https://ieeexplore.ieee.org/document/9773043)
- [Reshaping Viscoelastic-String  Path-Planner (RVP)](https://arxiv.org/pdf/2303.00947.pdf)


