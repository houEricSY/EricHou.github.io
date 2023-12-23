<!-- ---
title: "Neural Motion Graph"
collection: publications
permalink: /publications/paper-3
excerpt: 'Deep learning techniques have been employed to design a controllable human motion synthesizer. Despite their potential, however, designing a neural network-based motion synthesis that enables flexible user interaction, fine-grained controllability, and the support of new types of motions at reduced time and space consumption costs remains a challenge. In this paper, we propose a novel approach, a neural motion graph, that addresses the challenge by enabling scalability to new motions while using compact neural networks. Our approach represents each type of motion with a separate neural node to reduce the cost of adding new motion types. In addition, designing a separate neural node for each motion type enables task-specific control strategies and has greater potential to achieve a high-quality synthesis of complex motions, such as the Mongolian dance. Furthermore, a single transition network, which acts as neural edges, is used to model the transition between two motion nodes. The transition network is designed with a lightweight control module to achieve a fine-grained response to user control signals. Overall, the design choice makes the neural motion graph highly controllable and scalable. In addition to being fully flexible to user interaction through high-level and fine-grained user-control signals, our experimental and subjective evaluation results demonstrate that our proposed approach, neural motion graph, outperforms state-of-the-art human motion synthesis methods in terms of the quality of controlled motion generation. '
date: 2023-08-04
venue: 'ACM SIGGRAPH Asia 2023, Conference Tracking'
paperurl: 'https://dl.acm.org/doi/10.1145/3610548.3618181'
citation: 'Hongyu Tao, Shuaiying Hou, Changqing Zou, Hujun Bao, and Weiwei Xu. 2023. Neural Motion Graph. In SIGGRAPH Asia 2023 Conference Papers (SA '23). Association for Computing Machinery, New York, NY, USA, Article 84, 1–11. https://doi.org/10.1145/3610548.3618181'
---

[Download paper here](https://dl.acm.org/doi/10.1145/3610548.3618181)

Hongyu Tao, [**Shuaiying Hou**](https://houericsy.github.io/ShuaiyingHou/), [Changqing Zou](https://changqingzou.weebly.com/), [Hujun Bao](http://www.cad.zju.edu.cn/home/bao/), [Weiwei Xu](http://www.cad.zju.edu.cn/home/weiweixu/weiweixu_en.htm) -->

---
title: "A Two-part Transformer Network for Controllable Motion Synthesis"
collection: publications
permalink: /publications/paper-3
excerpt: 'Although part-based motion synthesis networks have been investigated to reduce the complexity of modeling heterogeneous human motions, their computational cost remains prohibitive in interactive applications. To this end, we propose a novel two-part transformer network that aims to achieve high-quality, controllable motion synthesis results in real-time. Our network separates the skeleton into the upper and lower body parts, reducing the expensive cross-part fusion operations, and models the motions of each part separately through two streams of auto-regressive modules formed by multi-head attention layers. However, such a design might not sufficiently capture the correlations between the parts. We thus intentionally let the two parts share the features of the root joint and design a consistency loss to penalize the difference in the estimated root features and motions by these two auto-regressive modules, significantly improving the quality of synthesized motions. After training on our motion dataset, our network can synthesize a wide range of heterogeneous motions, like cartwheels and twists. Experimental and user study results demonstrate that our network is superior to state-of-the-art human motion synthesis networks in the quality of generated motions.'
date: 2023-06-06
venue: 'IEEE Transactions on Visualization and Computer Graphics (TVCG)'
paperurl: 'https://ieeexplore.ieee.org/document/10147861'
citation: 'S. Hou, H. Tao, H. Bao and W. Xu, "A Two-part Transformer Network for Controllable Motion Synthesis," in IEEE Transactions on Visualization and Computer Graphics, doi: 10.1109/TVCG.2023.3284402.'
---

[Download paper here](https://ieeexplore.ieee.org/document/10147861)

<!-- Recommended citation: Your Name, You. (2010). "Paper Title Number 2." <i>Journal 1</i>. 1(2). -->
[**Shuaiying Hou**](https://houericsy.github.io/ShuaiyingHou/), Hongyu Tao, [Hujun Bao](http://www.cad.zju.edu.cn/home/bao/), [Weiwei Xu](http://www.cad.zju.edu.cn/home/weiweixu/weiweixu_en.htm)