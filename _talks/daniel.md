---
layout: default
type: "Talk"
date: 2021-01-15
name: "Daniel Rakita"
teaser: "Methods and Applications for Generating Accurate and Feasible Robot-arm Motions in Real-time"
link: "/talks/daniel"
---
## Speaker

Daniel Rakita is a Ph.D. student of computer science at the University of Wisconsin-Madison advised by Michael Gleicher and Bilge Mutlu.  He received a Bachelors of Music Performance from the Indiana University Jacobs School of Music in 2012. His research lies at the intersection of motion planning, trajectory optimization, shared-control, and human-robot interaction, and commonly involves creating motion optimization approaches that allow robot manipulators to move smoothly and accurately in real-time. 


Speaker Links: [Website](http://pages.cs.wisc.edu/~rakita/) - [Google Scholar](https://scholar.google.com/citations?user=1Y-cnCUAAAAJ&hl=en)

<iframe width="560" height="315" src="https://www.youtube.com/embed/GGWh9HRuACM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

## Abstract
In order to complete tasks, robots need to consistently calculate joint-space trajectories such that their end-effectors pass through the correct position, with the correct orientation, at the correct time.  In many cases, these trajectories must not only be accurate, i.e., avoiding large end-effector translation or orientation errors; and feasible, i.e., avoiding self-collisions, joint-space discontinuities, or kinematic singularities; but they must also be calculated quickly to afford robots the ability to act and react in uncertain or dynamic environments.  In this talk, I will overview technical methods we have developed that attempt to achieve such feasible, accurate, and time-sensitive robot-arm motions.  In particular, I will detail our inverse kinematics solver called RelaxedIK that utilizes both non-linear optimization and machine learning to achieve a smooth, feasible, and accurate end-effector to joint-space mapping on-the-fly.  I will highlight numerous ways we have applied our technical methods to real-world-inspired problems, such as mapping human-arm-motion to robot-arm-motion in real-time to afford effective shared-control interfaces and automatically moving a camera-in-hand robot in a remote setting to optimize a viewpoint for a teleoperator.  I will conclude with a preview of our ongoing and future work in this space.


---

#### Papers covered during the talk
* **Rakita, Daniel**, Bilge Mutlu, and Michael Gleicher. "RelaxedIK: Real-time Synthesis of Accurate and Feasible Robot Arm Motion." Robotics: Science and Systems. 2018 [link](http://www.roboticsproceedings.org/rss14/p43.pdf) - [video](https://www.youtube.com/watch?v=AhsQFJzB8WQ)

* **Rakita, Daniel**, et al. "Shared control–based bimanual robot manipulation." Science Robotics 4.30 (2019)
[link](https://graphics.cs.wisc.edu/Papers/2019/RMGH19/19_ScienceRobotics_preprint.pdf) - [video](https://www.youtube.com/watch?v=cGh0UncVxck)

* **Rakita, Daniel**, Bilge Mutlu, and Michael Gleicher. "An autonomous dynamic camera method for effective remote teleoperation." Proceedings of the 2018 ACM/IEEE International Conference on Human-Robot Interaction. 2018.
[link](https://graphics.cs.wisc.edu/Papers/2018/RMG18/18-HRI-Camera_preprint.pdf) - [video](https://www.youtube.com/watch?v=xvDwTJd8f4c)

* **Rakita, Daniel**, Bilge Mutlu, and Michael Gleicher. "Remote Telemanipulation with Adapting Viewpoints in Visually Complex Environments." Robotics: Science and Systems. 2019
[link](http://www.roboticsproceedings.org/rss15/p68.pdf) - [video](https://www.youtube.com/watch?v=2JyNU2O5onc)

