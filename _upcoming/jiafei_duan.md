---
teaser: "Beyond Imitation: VLMs as Rewards, Steerers, and Reasoners for Robot Learning"
collection: upcoming
permalink: /upcoming/jiafei_duan
date: 2026-05-13
time: "9 AM PDT | 12 PM EDT | 6PM CEST"
venue: "Zoom"
name: "Jiafei Duan"
link: "/talks/jiafei_duan"
register: "https://us02web.zoom.us/meeting/register/fQYEmqUNSJate4qT9h1Ueg"
abstract: >
    Vision-Language-Action (VLA) models have made rapid progress in pretraining, but turning them into reliable, generalizable robots still runs into familiar walls — sparse rewards, brittle out-of-distribution behavior, and policies that act without explainable plans. This talk argues the missing piece isn't more action data; it's putting pretrained vision-language knowledge to work in three complementary roles inside the action-generation loop.

    I'll walk through three recent works, each occupying one role. TOPReward treats VLMs as evaluators, extracting dense, zero-shot reward signals directly from the token logits of off-the-shelf video VLMs — no calibration, no annotation, and strong correlation with true task progress across 130+ real-world manipulation tasks. Vision-Language Steering (VLS) turns VLMs into correctors, synthesizing differentiable rewards at inference time to steer frozen diffusion and flow-matching policies toward trajectories that satisfy out-of-distribution scenes and instructions — without any fine-tuning. MolmoAct2 then bakes the VLM in as the reasoner, predicting adaptive depth-aware perception tokens yielding behavior that is both more performant and more steerable than monolithic VLAs.
    
    Together, these works sketch a path beyond imitation: a stack in which pretrained VLMs reward, steer, and reason about action — making robot learning more sample-efficient, more robust to distribution shift, and more transparent.
---
