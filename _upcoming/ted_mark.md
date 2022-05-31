---
layout: talk
type: "Talk"
date: 2022-06-08
name: ""
teaser: "Learning Rewards from Natural Language"
link: "/upcoming/ted_mark" 
register: 
author_profile: true
---


## Speakers

I'm a third-year PhD student advised by Tom Griffiths at Princeton and supported by a NDSEG fellowship. My research uses reinforcement learning and decision theory to study human communication. Theoretically, I'm interested in explaining how societies accumulate information over generations. Practically, I hope to develop artificial systems capable of interacting with and learning from humans. Prior to beginning my PhD, I was a data scientist and engineering manager at Automatic Labs (2013-2014) and Uber (2014-2019). 

[AAAI'21](https://arxiv.org/abs/2009.14715)
[ACL '22 - workshop on Learning from Natural Language Supervision](https://arxiv.org/abs/2204.05091)
---

## Abstract
We'll talk about methods to learn humans' reward functions from natural language input. While robotics has historically focused on learning from natural language instructions, we find that humans prefer to teach with rich evaluative and descriptive feedback. To learn from this naturalistic language, we develop a new sentiment-analysis based approach: we decompose feedback into sentiment about the features of a Markov decision process. We then perform an analogue of Bayesian inverse reinforcement learning, regressing the sentiment on the features to infer the teacher's latent reward function. Behavioral experiments validate that this agent successfully recovers humans' reward functions from natural language input. Finally, we'll cover more recent theoretical work that seeks to explain how a rational speaker should use these different forms of language.