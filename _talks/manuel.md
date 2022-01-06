---
layout: default
type: "Talk"
date: 2020-11-27
name: "Manuel Bied"
teaser: "Integrating an Observer in Interactive Reinforcement Learning to Learn Legible Trajectories"
link: "/talks/manuel"
---
## Speaker

Manuel Bied is a PhD student at Institut des Systèmes Intelligents et de Robotique (ISIR) at Sorbonne Université supervised by Prof. Mohamed Chetouani. In his research he’s interested in integrating pedagogical reasoning with robot learning strategies as Reinforcement Learning and Learning-from-Demonstration. He is part of the MSCA-Innovative Training Network ANIMATAS. Prior to joining ISIR he received a B.Sc. and M.Sc. degree in Electrical Engineering from TU Darmstadt (Germany). His Master’s thesis about Learning-from-Demonstration was conducted in cooperation with Honda Research Institute Europe and supervised by Prof. Jan Peters.

<iframe width="560" height="315" src="https://www.youtube.com/embed/xjYcM3zWkZM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
---

## Abstract
An important aspect of Human-Robot-cooperation is that the robot is capable of clearly communicating its intentions to its human collaborator. This communication of intentions often requires the generation of legible motion trajectories. The concept of legible motion is usually not studied together with machine learning. Studying these fields together is an important step towards better Human-Robot cooperation. In this paper, we investigate interactive robot learning approaches with the aim of developing models that are able to generate legible motions by taking observer feedback  into account. We explore how to integrate the observer feedback into a Reinforcement Learning (RL) framework. We do this by proposing three different observer algorithms as observer strategies in an interactive RL scheme and compare with one non-interactive RL algorithm as baseline. For the observer strategies we vary the method how the observer estimates how likely the agent is going for the target goal. We evaluate our approach on five environments and calculate the legibility of the learned trajectories. The results show that the legibility of the learned trajectories is significantly higher while integrating the feedback from the observer compared with a standard Q-Learning algorithm not using the observer feedback.

---

#### Papers covered during the talk
* **Bied, M.** and Chetouani, M. (2020). Integrating an Observer in Interactive Reinforcement Learning to Learn Legible Trajectories. The 29th IEEE International Conference on Robot and Human Interactive Communication, RO-MAN Pages to appear. Napoli, Italy.