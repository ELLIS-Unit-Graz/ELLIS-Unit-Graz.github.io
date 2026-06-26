---
title: Probabilistic Machine Learning
---

# {% include icon.html icon="fa-solid fa-chart-pie" %}Probabilistic Machine Learning

**Probabilistic Machine Learning**

Probabilistic machine learning treats probability not merely as a statistical tool, but as a language for rational reasoning under uncertainty — the natural counterpart of logic. While logic tells us what follows from facts that are certainly true, probability allows us to reason when knowledge is incomplete, noisy, or ambiguous. This perspective places uncertainty at the heart of machine learning: rather than producing single point predictions, probabilistic models quantify what is known, what is unknown, and how beliefs should update in light of new evidence. Our group is at the forefront of making this vision practical, developing methods that are not only theoretically principled but scalable and deployable in real-world systems.

**Approaches:**

A central thread in our research is the Bayesian framework, which provides a principled way to incorporate prior knowledge and update beliefs from data. Bayesian methods yield full posterior distributions over model parameters and predictions, enabling calibrated uncertainty estimates that are critical in high-stakes settings. A particularly powerful application of Bayesian thinking is Bayesian optimization, which models the objective function probabilistically and guides the search for optima in a sample-efficient manner. This makes it well suited for expensive black-box problems, including the design of molecules or enzymes in scientific discovery as well as hyperparameter tuning in modern AI pipelines.

A key challenge in probabilistic machine learning is that exact inference — computing marginals, conditionals, or expectations — is generally computationally intractable for expressive models. Our group addresses this challenge head-on through tractable probabilistic models, most prominently probabilistic circuits. Probabilistic circuits represent complex joint distributions as structured computational graphs that guarantee tractability for a wide range of inference queries, including marginalization, conditioning, and maximization. Pioneering work by Robert Peharz, including the development of Einsum Networks, has made probabilistic circuits significantly more scalable and practical, bringing tractable probabilistic reasoning into the deep learning era.

Probabilistic graphical models unite probability and graph theory, providing a flexible and powerful language for encoding structured dependencies among random variables. Franz Pernkopf has contributed extensively to this area, covering both discriminative and generative learning paradigms, with applications ranging from speech and signal processing to dependable AI for industry and medicine. Graphical models form the backbone of many probabilistic reasoning systems and connect naturally to both tractable inference and causal modeling.

Causal models extend probabilistic reasoning beyond statistical association to capture cause-and-effect relationships, enabling principled reasoning about interventions and counterfactuals — questions purely correlational models cannot answer. As a particularly interesting direction, we develop Bayesian causal inference methods that avoid committing to a single causal graph and instead maintain a full posterior over causal structures, yielding more robust and uncertainty-aware causal reasoning. This is essential wherever understanding the effect of actions matters, from scientific experimentation to robust decision-making.

Rounding out our agenda, Bernhard Geiger's research draws on information theory to deepen the understanding of machine learning methods, using concepts such as entropy, mutual information, and information bottleneck principles both as analytical tools and as learning objectives. With these approaches, we work towards understanding the fundamental limits of deep learning and instill operational goals into neural models via variational approaches.

Together, these complementary strengths — tractable inference, Bayesian methods, graphical and causal models, and information-theoretic foundations — make our group a uniquely powerful hub for probabilistic machine learning research, with impact reaching from core methodology to applications in science, engineering, and beyond.

Involved researchers: [Robert Peharz](https://ellis-unit-graz.github.io/members/robert-peharz.html), [Bernhard Geiger](https://ellis-unit-graz.github.io/members/bernhard-geiger.html), [Franz Pernkopf](https://ellis-unit-graz.github.io/members/franz-pernkopf.html)