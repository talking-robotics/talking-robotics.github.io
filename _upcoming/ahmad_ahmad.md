---
teaser: "Quantitative Temporal Logic for Safe and Robust Planning, Learning, and Control"
collection: upcoming
permalink: /upcoming/ahmad_ahmad
date: 2026-06-17
time: "9 AM PDT | 12 PM EDT | 6PM CEST"
venue: "Zoom"
name: "Ahmad Ahmad"
link: "/talks/ahmad_ahmad"
register: "https://us02web.zoom.us/meeting/register/Xa9XYGscSdKB61Fd3-56JA"
abstract: >
    Temporal logics offer a principled and interpretable framework for expressing complex spatiotemporal tasks in autonomous systems. However, classical Boolean semantics are too coarse to guide planning, learning, or control: they do not distinguish how well a specification is satisfied, only whether it is. This talk presents a line of research that addresses this gap through quantitative semantics for temporal logic, and demonstrates how these richer robustness measures can be leveraged across three interconnected settings.

    First, we introduce quantitative semantics for Time Window Temporal Logic (TWTL), a specification language that natively expresses tasks with explicit time windows. We define two robustness measures and corresponding online monitoring algorithms that enable real-time quantification of satisfaction along trajectories of discrete-time systems.

    Second, we show how temporal logic specifications with robustness-based reward shaping can accelerate reinforcement learning under delayed rewards. We augment Proximal Policy Optimization with a hybrid policy architecture and a TWTL-based reward shaping mechanism, proving monotonic improvement guarantees over both offline and online policies.

    Third, we present RRT-eta, a sampling-based motion planning framework that integrates Arithmetic-Geometric Mean (AGM) robustness to guide tree exploration under STL specifications. Unlike min-max robustness, AGM evaluates satisfaction across all time points and subformulae, producing smoother optimization landscapes. We introduce interval semantics for reasoning about partial trajectories during tree construction, along with an incremental monitoring algorithm that makes this approach computationally tractable.
    
    Together, these contributions form a coherent arc: quantitative temporal logic not only measures satisfaction, it actively shapes how autonomous systems plan, learn, and act.
---
