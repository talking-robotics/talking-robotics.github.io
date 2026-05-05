---
layout: talk
type: "Talk"
date: 2026-05-13
name: "Jiafei Duan"
teaser: "Beyond Imitation: VLMs as Rewards, Steerers, and Reasoners for Robot Learning"
link: "/talks/jiafei_duan"
---


### Speaker
Jiafei Duan is an incoming Assistant Professor at the National University of Singapore, School of Computing. He completed his Ph.D. in Computer Science & Engineering at the University of Washington, where he was advised by Professors Dieter Fox and Ranjay Krishna. His work lies at the intersection of robotics and computer vision, with a focus on robotics foundation models — particularly scalable data collection and generation, grounding vision–language models in robotic reasoning, and improving robust generalization in robot learning. His research has been featured in MIT Technology Review, GeekWire, VentureBeat, and Business Wire, and has appeared at top AI and robotics venues including ICLR, ICML, RSS, CoRL, ECCV, IJCAI, CoLM, and EMNLP. Among his honors are the Best Paper Award at Ubiquitous Robots 2023, the Best Paper Award at the CoRL RememberRL Workshop 2025, and a Spotlight Award at ICLR 2024.


### Abstract
Vision-Language-Action (VLA) models have made rapid progress in pretraining, but turning them into reliable, generalizable robots still runs into familiar walls — sparse rewards, brittle out-of-distribution behavior, and policies that act without explainable plans. This talk argues the missing piece isn't more action data; it's putting pretrained vision-language knowledge to work in three complementary roles inside the action-generation loop.


I'll walk through three recent works, each occupying one role. TOPReward treats VLMs as evaluators, extracting dense, zero-shot reward signals directly from the token logits of off-the-shelf video VLMs — no calibration, no annotation, and strong correlation with true task progress across 130+ real-world manipulation tasks. Vision-Language Steering (VLS) turns VLMs into correctors, synthesizing differentiable rewards at inference time to steer frozen diffusion and flow-matching policies toward trajectories that satisfy out-of-distribution scenes and instructions — without any fine-tuning. MolmoAct2 then bakes the VLM in as the reasoner, predicting adaptive depth-aware perception tokens yielding behavior that is both more performant and more steerable than monolithic VLAs.


Together, these works sketch a path beyond imitation: a stack in which pretrained VLMs reward, steer, and reason about action — making robot learning more sample-efficient, more robust to distribution shift, and more transparent.


<iframe width="1404" height="790" src="https://www.youtube.com/embed/pOYgp-J5plw" title="Jiafei Duan - MolmoAct2" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
