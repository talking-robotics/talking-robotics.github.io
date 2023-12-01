---
layout: talk
type: "Talk"
date: 2023-12-07
name: "Ankit J. Shah"
teaser: "How (temporal) reward abstractions help planning and task understanding"
link: "/upcoming/ankit_shah"
register: "https://us02web.zoom.us/meeting/register/tZctce2qrTgpH9xXWuYdkYAUKDC6kL07MaEb#/registration"
---


### Speaker 
Ankit recently started as a research scientist at the [Boston Dynamics AI Institute](https://theaiinstitute.com/). His research focuses on developing computational models that allow domain-experts to directly train autonomous agents just as they would train a human apprentice. Previously Ankit was a postdoctoral researcher at Brown University with Profs. Stefanie Tellex and George Konidaris. Ankit completed his Ph.D. at the Interactive Robotics Group with Prof. Jule Shah at MIT.

Speaker Links: [Google scholar](https://scholar.google.com/citations?user=KmJNnzIAAAAJ&hl=en)


### Abstract
Temporal reward abstractions frameworks such as linear temporal logic help with generating a compact description of acceptable trajectories of the world state. While these reward descriptions when translated to automata can help speed up planning and learning by providing a reward scaffold, this talk explores some other utilities of reward definitions using beliefs over LTL formulas. Specifically, I will talk about two use cases. First, where belief over LTL specifications can be used to generate active learning query trajectories are used to prune the belief space over task specifications efficiently, allowing the robot to learn high quality task specifications even if starting from a highly uncertain belief. Next, we demonstrate how models that translate natural language to formal specifications can leverage compositional structure to adapt to novel domains without any additional domain specific training.


### Papers
- [Interactive Robot Training for Non-Markov Tasks](https://people.csail.mit.edu/ajshah/project/interactive/)
- [Grounding Complex Natural Language Commands for Temporal Tasks in Unseen Environments](https://lang2ltl.github.io/)