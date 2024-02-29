---
layout: talk
type: "Talk"
date: 2024-03-07
name: "Anushri Dixit"
teaser: "Perceive with Confidence: Statistical Safety Assurances for Vision-based Navigation"
link: "/upcoming/anushri_dixit"
register: "https://us02web.zoom.us/meeting/register/tZEkf-usqTsvG9YMPexnLIToi_Bnt4SM75MA"
---


### Speaker 
Anushri Dixit is a Postdoctoral Researcher in the Department of Mechanical & Aerospace Engineering at Princeton University. She received her Ph.D. in Control and Dynamical Systems from California Institute of Technology in 2023 and her B.S. in Electrical Engineering from Georgia Institute of Technology in 2017. Her research focuses on motion planning and control of robots in unstructured environments while accounting for uncertainty in a principled manner. Her work on risk-aware methodologies for planning has been deployed on various robotic platforms as a part of Team CoSTAR’s effort in the DARPA Subterranean Challenge. She has received the Outstanding Student Paper Award at the Conference on Decision and Control, Best Student Paper Award at the Conference of Robot Learning, and was selected as a Rising Star in Data Science by The University of Chicago. She will start as an Assistant Professor at the University of California, Los Angeles in Mechanical and Aerospace Engineering in July 2024.

Speaker Links: [Google Scholar](https://scholar.google.com/citations?user=ADThnCAAAAAJ), [Website](https://www.anushridixit.com/)


### Abstract
Significant strides in perception over the past few years have enabled robotic systems to interpret and interact with the world in increasingly versatile ways. The large, often multi-modal, datasets that are used to train modern perception systems endow robots with capabilities for scene understanding like object detection and segmentation. However, the safe integration and reliability of these learned perception models for robotics applications still remains in question due to their failures in unfamiliar environments. In this talk, I will discuss our framework, Perceive with Confidence (PwC), for rigorously quantifying the uncertainty of a pre-trained obstacle detection system in a way that provides a formal assurance on correctness and safety for planning applications. This is achieved by utilizing a technique called conformal prediction to calibrate the perceptual outputs while ensuring generalization to novel environments. I will provide experimental validations of PwC's formal assurances for indoor navigation applications on the Unitree Go1 quadruped.