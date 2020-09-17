---
layout: default
---
## Speaker
<!--<img src="assets/img/mike.jpg" alt="mike" width="270"/>-->

Hang is a post-doctoral researcher at the Robotics, Perception, and Learning Group, KTH Royal Institute of Technology. He is co-leading the research direction of deformable object manipulation by co-supervising PhD students and doing his research. 

---

## Abstract
Exploiting efficient representations is the key to learning and automating real-world robotic tasks. In this talk, I will present recent results at RPL about learning state or modeling action spaces for roboticagents to address challenging manipulation tasks. In the first part, I will present a framework of learning a compact representation to encode high-dimensional and complex state/observations, e.g. configurations of a clothing item. I will show a variant of variational autoencoders which imposes a low-dimensional latent space with an improved structure. This allows us to build a roadmap in the embedding space and perform effective action planning in a cloth folding task. In the second part, the talk will focus on incorporating well-established robot control results in the reinforcement learning action design. I will introduce a policy in the form of a stable variable impedance controller and a variant of Cross Entropy Method to guarantee stable explorations in learning contact-rich skills. Our results demonstrate a superior performance in simulated and real-world peg-in-hole tasks, despite of admitting a more restricted class of behaviors comparing to baseline neural network policies.

---

#### Papers covered during the talk
* Lippi, M., Poklukar, P., Welle, M.C., Varava, A., **Yin, H.**, Marino, A., & Kragic, D. (2020). Latent Space Roadmap for Visual Action Planning of Deformable and Rigid Object Manipulation. ArXiv, abs/2003.08974.
* Khader, S.A., **Yin, H.**, Falco, P., & Kragic, D. (2020). Stability-Guaranteed Reinforcement Learning for Contact-rich Manipulation. ArXiv, abs/2004.10886.
