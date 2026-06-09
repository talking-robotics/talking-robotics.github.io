---
layout: talk
type: "Talk"
date: 2026-06-17
name: "Ahmad Ahmad"
teaser: "Quantitative Temporal Logic for Safe and Robust Planning, Learning, and Control"
link: "/talks/ahmad_ahmad"
---


### Speaker
Ahmad Ahmad is a postdoctoral researcher fellow in the Automata Lab at Worcester Polytechnic Institute, working with Professor Kevin Leahy. He earned his Ph.D. in Systems Engineering from Boston University, where he was co-advised by Professor Calin Belta and by Professor Roberto Tron. His research sits at the intersection of formal methods, motion planning, and reinforcement learning, with a focus on using temporal logic specifications to enable safe and interpretable behavior in autonomous systems. His work spans the full pipeline from specification and verification to control synthesis and learning, with contributions to quantitative semantics, runtime monitoring, sampling-based planning, and reward shaping for learning under complex spatiotemporal constraints.

### Abstract
Temporal logics offer a principled and interpretable framework for expressing complex spatiotemporal tasks in autonomous systems. However, classical Boolean semantics are too coarse to guide planning, learning, or control: they do not distinguish how well a specification is satisfied, only whether it is. This talk presents a line of research that addresses this gap through quantitative semantics for temporal logic, and demonstrates how these richer robustness measures can be leveraged across three interconnected settings.

First, we introduce quantitative semantics for Time Window Temporal Logic (TWTL), a specification language that natively expresses tasks with explicit time windows. We define two robustness measures and corresponding online monitoring algorithms that enable real-time quantification of satisfaction along trajectories of discrete-time systems.

Second, we show how temporal logic specifications with robustness-based reward shaping can accelerate reinforcement learning under delayed rewards. We augment Proximal Policy Optimization with a hybrid policy architecture and a TWTL-based reward shaping mechanism, proving monotonic improvement guarantees over both offline and online policies.

Third, we present RRT-eta, a sampling-based motion planning framework that integrates Arithmetic-Geometric Mean (AGM) robustness to guide tree exploration under STL specifications. Unlike min-max robustness, AGM evaluates satisfaction across all time points and subformulae, producing smoother optimization landscapes. We introduce interval semantics for reasoning about partial trajectories during tree construction, along with an incremental monitoring algorithm that makes this approach computationally tractable.

Together, these contributions form a coherent arc: quantitative temporal logic not only measures satisfaction, it actively shapes how autonomous systems plan, learn, and act.

#### Papers Covered
- [https://arxiv.org/pdf/2304.06645](https://arxiv.org/pdf/2304.06645)
- [https://arxiv.org/pdf/2411.17861](https://arxiv.org/pdf/2411.17861)
- [https://arxiv.org/pdf/2602.16825](https://arxiv.org/pdf/2602.16825)