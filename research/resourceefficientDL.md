---
title: Resource-efficient Deep Learning
---

# {% include icon.html icon="fa-solid fa-hexagon-nodes" %}Resource-efficient Deep Learning

Resource-efficient machine learning focuses on developing models and training methods that achieve strong predictive performance while minimizing the use of computational, memory, energy, and data resources. As machine learning systems grow in scale and complexity, the cost of training and deploying models has increased substantially. Large models require extensive computational infrastructure and consume significant energy during training and inference. At the same time, many applications--such as mobile devices and embedded systems--operate under strict hardware and energy constraints. Resource-efficient machine learning addresses these challenges by designing algorithms and systems that maintain high performance while reducing resource consumption.

**Approaches:**
- One important aspect of resource-efficient machine learning is the design of efficient model architectures. Instead of relying on increasingly large models, the goal is to develop architectures that achieve comparable accuracy with fewer parameters and computational operations. Techniques such as parameter sharing, sparse connections, and lightweight architectural building blocks can significantly reduce computational cost and memory footprint.

- Another central approach is model compression, which reduces the size and complexity of trained models without substantially degrading accuracy. Common methods include pruning, quantization, low-rank approximations, and model folding. Pruning removes weights or neurons that contribute little to predictions, quantization reduces the numerical precision of parameters, and model folding merges similar neurons or channels by clustering their weights into shared representations.

- Knowledge distillation improves efficiency by transferring knowledge from a large, accurate model (the teacher) to a smaller model (the student). By learning to mimic the teacher’s predictions or internal representations, the student can achieve much of the teacher’s performance while requiring significantly fewer parameters and computations.

- Biologically inspired spiking neural networks (SNNs) are inherently resource-efficient due to their event-driven computation. Unlike conventional neural networks that perform continuous operations, SNNs process information through discrete spikes and update neurons only when relevant events occur. This leads to sparse activity and reduced computational and energy costs, making SNNs well suited for neuromorphic hardware and edge devices.

- Another important dimension is data efficiency. Since collecting labeled data is often expensive, approaches such as transfer learning, self-supervised learning, and few-shot learning aim to reduce the amount of labeled data required by leveraging previously learned representations or unlabeled data.

Overall, resource-efficient machine learning aims to make effective use of limited computational and energy resources while maintaining high model quality. Advances in efficient architectures, compression methods, and data-efficient training will play a key role in making machine learning systems more scalable, sustainable, and widely accessible.


Involved researchers: [Wolfgang Maass](https://ellis-unit-graz.github.io/members/wolfgang-maass.html), [Robert Legenstein](https://ellis-unit-graz.github.io/members/robert-legenstein.html), [Franz Pernkopf](https://ellis-unit-graz.github.io/members/franz-pernkopf.html), [Olga Saukh](https://ellis-unit-graz.github.io/members/olga-saukh.html), [Ozan Özdenizci](https://ellis-unit-graz.github.io/ozan-oezdenizci.html)