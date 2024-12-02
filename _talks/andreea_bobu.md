---
layout: talk
type: "Talk"
date: 2024-11-13
name: "Andreea Bobu"
teaser: "Aligning Robot and Human Representations"
link: "/talks/andreea_bobu"
---


### Speaker 
 Andreea Bobu is an Assistant Professor at MIT in AeroAstro and CSAIL. She leads the [Collaborative Learning and Autonomy Research Lab (CLEAR Lab)](https://clear.csail.mit.edu/index.html), where they develop autonomous agents that learn to do tasks for, with, and around people. Her goal is to ensure that these agents' behavior is consistent with human expectations, whether they interact with expert designers or novice users. She obtained her Ph.D. in Electrical Engineering and Computer Science at UC Berkeley with Anca Dragan in 2023. Prior to her Ph.D. she earned her Bachelor’s degree in Computer Science and Engineering from MIT in 2017. She was the recipient of the Apple AI/ML Ph.D. fellowship, is a Rising Star in EECS and an R:SS and HRI Pioneer, and has won best paper award at HRI 2020 and the Emerging Research Award at the International Symposium on the Mathematics of Neuroscience 2023. Before MIT, she was also a Research Scientist at the AI Institute and an intern at NVIDIA in the Robotics Lab.

Speaker Links: [Website](https://www.mit.edu/~abobu/), [Google Scholar](https://scholar.google.com/citations?user=62e5CygAAAAJ)


### Abstract 
To perform tasks that humans want in the world, robots rely on a *representation* of salient task features; for example, to hand me a cup of coffee, the robot considers features like efficiency and cup orientation in its behavior. Prior methods try to learn both a representation and a downstream task jointly from data sets of human behavior, but this unfortunately picks up on spurious correlations and results in behaviors that do not generalize. In my view, *what’s holding us back from successful human-robot interaction is that human and robot representations are often misaligned:* for example, our assistive robot moved a cup inches away from my face -- which is technically collision-free behavior -- because it lacked an understanding of personal space. Instead of treating people as static data sources, my key insight is that **robots must engage with humans in an interactive process for finding a shared representation** for more efficient, transparent, and seamless downstream learning. In this talk, I focus on a divide and conquer approach: *explicitly focus human input on teaching robots good representations before using them for learning downstream tasks.* This means that instead of relying on inputs designed to teach the representation implicitly, we have the opportunity to design human input that is explicitly targeted at teaching the representation and can do so efficiently. I introduce a new type of *representation-specific input* that lets the human teach new features, I enable robots to reason about the uncertainty in their current representation and automatically *detect misalignment*, and I propose a *novel human behavior model* to learn robust behaviors on top of human-aligned representations. By explicitly tackling representation alignment, I believe we can ultimately achieve seamless interaction with humans where each agent truly grasps why the other behaves the way they do.
