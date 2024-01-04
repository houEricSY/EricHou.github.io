---
title: "A Two-part Transformer Network for Controllable Motion Synthesis"
collection: publications
permalink: /publications/paper-2
excerpt: 'Although part-based motion synthesis networks have been investigated to reduce the complexity of modeling heterogeneous human motions, their computational cost remains prohibitive in interactive applications. To this end, we propose a novel two-part transformer network that aims to achieve high-quality, controllable motion synthesis results in real-time. Our network separates the skeleton into the upper and lower body parts, reducing the expensive cross-part fusion operations, and models the motions of each part separately through two streams of auto-regressive modules formed by multi-head attention layers. However, such a design might not sufficiently capture the correlations between the parts. We thus intentionally let the two parts share the features of the root joint and design a consistency loss to penalize the difference in the estimated root features and motions by these two auto-regressive modules, significantly improving the quality of synthesized motions. After training on our motion dataset, our network can synthesize a wide range of heterogeneous motions, like cartwheels and twists. Experimental and user study results demonstrate that our network is superior to state-of-the-art human motion synthesis networks in the quality of generated motions.'
date: '2023-06-06'
venue: 'IEEE Transactions on Visualization and Computer Graphics (TVCG)'
paperurl: 'https://ieeexplore.ieee.org/document/10147861'
citation: 'S. Hou, H. Tao, H. Bao and W. Xu, "A Two-part Transformer Network for Controllable Motion Synthesis," in IEEE Transactions on Visualization and Computer Graphics, doi: 10.1109/TVCG.2023.3284402.'
---

[Download paper here](https://ieeexplore.ieee.org/document/10147861)

<!-- Recommended citation: Your Name, You. (2010). "Paper Title Number 2." <i>Journal 1</i>. 1(2). -->
[**Shuaiying Hou**](https://houericsy.github.io/ShuaiyingHou/), Hongyu Tao, [Hujun Bao](http://www.cad.zju.edu.cn/home/bao/), [Weiwei Xu](http://www.cad.zju.edu.cn/home/weiweixu/weiweixu_en.htm)


**BibTeX**\
@ARTICLE{10147861,\
  author={Hou, Shuaiying and Tao, Hongyu and Bao, Hujun and Xu, Weiwei},\
  journal={IEEE Transactions on Visualization and Computer Graphics}, \
  title={A Two-part Transformer Network for Controllable Motion Synthesis}, \
  year={2023},\
  volume={},\
  number={},\
  pages={1-16},\
  doi={10.1109/TVCG.2023.3284402}\
  }