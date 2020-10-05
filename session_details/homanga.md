---
layout: default
---
## Speaker
<!--<img src="assets/img/mike.jpg" alt="mike" width="270"/>-->

Homanga Bharadhwaj is a second year graduate student in the Department of Computer Science at the University of Toronto. He is a member of the Computer Science Robotics Group, and the Vector Institute, Toronto. His research interests are in robot learning, and in particular learning efficient and safe policies for exploration. 

Speaker Links: [Website](https://homangab.github.io/) - [GitHub](https://github.com/homangab/) - [Google Scholar](https://scholar.google.ca/citations?user=wwW4HRQAAAAJ&hl=en) - [Twitter](https://twitter.com/mangahomanga)

---
## Abstract
Transferring control policies to different environments with minimal fine-tuning is an important challenge in robotics. It is important to learn high-performing policies that can adapt to dynamics variations in the environment, for achieving sample efficient learning, and in ensuring safety of the robot and the environment. In this talk, I will describe the problem of transferring policies across multiple environments with different dynamics parameters and motor noise variations, and introduce a framework that decouples the processes of policy learning and system identification. The approach is called MANGA: Method Agnostic Neural-policy Generalization and Adaptation, whose key idea is training dynamics conditioned policies and efficiently learning to estimate the dynamics parameters of the environment given off-policy state-transition rollouts. I'll also discuss how some other recent papers have approached this problem, and why it is important to learn policies that are adaptive instead of being robust.

---

#### Papers covered during the talk
* **Bharadhwaj, H.**, Yamaguchi, S., & Maeda, S. I. (2019). MANGA: Method Agnostic Neural-policy Generalization and Adaptation. [link](https://arxiv.org/pdf/1911.08444.pdf).
