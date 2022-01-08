---
layout: talk
type: "Talk"
date: 2020-09-25
name: "Hang Yin"
teaser: "Efficient Representations in Learning Visual Planning and Contact-rich Tasks"
link: "/talks/hang"
---
## Speaker
Hang is a Postdoctoral Researcher at the Robotics, Perception and Learning Group, KTH Royal Institute of Technology. Hang’s interests lie in the intersection of robotics and machine learning and he is enthusiastic about finding and integrating problem structures, such as task representation, dynamical systems and optimization-based control, to facilitate learning-based robotics.
Hang obtained his PhD from EPFL and IST, University of Lisbon under the supervision of Prof. Aude Billard, Prof. Ana Paiva and Prof. Francisco S. Melo. Prior to that, Hang completed his master and bachelor studies in Shanghai Jiao Tong University. He also worked as a software engineer in Siemens.

Speaker Links: [Website](https://navigator8972.github.io) - [GitHub](https://github.com/navigator8972) - [Google Scholar](https://scholar.google.pt/citations?user=7VW7URUAAAAJ&hl=en)

<iframe width="560" height="315" src="https://www.youtube.com/embed/esTYcbd-Wp8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
---

## Abstract
Exploiting efficient representations is the key to learning and automating real-world robotic tasks. In this talk, I will present recent results at RPL about learning state or modeling action spaces for roboticagents to address challenging manipulation tasks. In the first part, I will present a framework of learning a compact representation to encode high-dimensional and complex state/observations, e.g. configurations of a clothing item. I will show a variant of variational autoencoders which imposes a low-dimensional latent space with an improved structure. This allows us to build a roadmap in the embedding space and perform effective action planning in a cloth folding task. In the second part, the talk will focus on incorporating well-established robot control results in the reinforcement learning action design. I will introduce a policy in the form of a stable variable impedance controller and a variant of Cross Entropy Method to guarantee stable explorations in learning contact-rich skills. Our results demonstrate a superior performance in simulated and real-world peg-in-hole tasks, despite of admitting a more restricted class of behaviors comparing to baseline neural network policies.

---

#### Papers covered during the talk
* Lippi, M., Poklukar, P., Welle, M.C., Varava, A., **Yin, H.**, Marino, A., & Kragic, D. (2020). Latent Space Roadmap for Visual Action Planning of Deformable and Rigid Object Manipulation. [ArXiv, abs/2003.08974](https://arxiv.org/pdf/2003.08974.pdf).
* Khader, S.A., **Yin, H.**, Falco, P., & Kragic, D. (2020). Stability-Guaranteed Reinforcement Learning for Contact-rich Manipulation. [ArXiv, abs/2004.10886](https://arxiv.org/pdf/2004.10886.pdf).
