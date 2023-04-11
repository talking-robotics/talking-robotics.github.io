---
layout: talk
type: "Talk"
date: 2023-03-22
name: "Saurabh Garg"
teaser: "Domain Adaptation under Relaxed Label Shift"
link: "/upcoming/sebastian"
register: ""
---

### Speaker 
Saurabh Garg is a fourth-year Ph.D. student in the Machine Learning Department at Carnegie Mellon University, advised by Zachary Lipton and Sivaraman Balakrishnan. Saurabh is interested in building robust and deployable machine learning systems. The primary focus of his research is to improve and evaluate deep learning models in the face of distribution shifts.  Before Saurabh started his Ph.D., he received his bachelor’s degree from the Indian Institute of Technology (IIT) Bombay, majoring in Computer Science and Engineering. 

[project website](https://sites.google.com/view/rlsbench/)

### Abstract 
Despite the emergence of principled methods for domain adaptation under label shift, the sensitivity of these methods for minor shifts in the class conditional distributions remains precariously under-explored. Meanwhile, popular deep-domain adaptation heuristics tend to falter when faced with shifts in label proportions. While several papers attempt to adapt these heuristics to accommodate shifts in label proportions, inconsistencies in evaluation criteria, datasets, and baselines, make it hard to assess the state of the art. In this paper, we introduce RLSbench, a large-scale \emph{relaxed label shift} benchmark, consisting of $>$500 distribution shift pairs that draw on 14 datasets across vision, tabular, and language modalities and compose them with varying label proportions. First, we evaluate 13 popular domain adaptation methods, demonstrating more widespread failures under label proportion shifts than were previously known. Next, we develop an effective two-step meta-algorithm that is compatible with most deep domain adaptation heuristics: (i) pseudo-balance the data at each epoch; and (ii) adjust the final classifier with (an estimate of) target label distribution. The meta-algorithm improves existing domain adaptation heuristics often by 2--10\% accuracy points under extreme label proportion shifts and has little (i.e., $<$0.5\%) effect when label proportions do not shift. We hope that these findings and the availability of RLSbench will encourage researchers to rigorously evaluate proposed methods in relaxed label shift settings. 

Relevant [paper](https://arxiv.org/abs/2302.03020)
