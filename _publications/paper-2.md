---
title: "Neural Motion Graph"
collection: publications
permalink: /publications/paper-2
excerpt: 'Deep learning techniques have been employed to design a controllable human motion synthesizer. Despite their potential, however, designing a neural network-based motion synthesis that enables flexible user interaction, fine-grained controllability, and the support of new types of motions at reduced time and space consumption costs remains a challenge. In this paper, we propose a novel approach, a neural motion graph, that addresses the challenge by enabling scalability to new motions while using compact neural networks. Our approach represents each type of motion with a separate neural node to reduce the cost of adding new motion types. In addition, designing a separate neural node for each motion type enables task-specific control strategies and has greater potential to achieve a high-quality synthesis of complex motions, such as the Mongolian dance. Furthermore, a single transition network, which acts as neural edges, is used to model the transition between two motion nodes. The transition network is designed with a lightweight control module to achieve a fine-grained response to user control signals. Overall, the design choice makes the neural motion graph highly controllable and scalable. In addition to being fully flexible to user interaction through high-level and fine-grained user-control signals, our experimental and subjective evaluation results demonstrate that our proposed approach, neural motion graph, outperforms state-of-the-art human motion synthesis methods in terms of the quality of controlled motion generation.'
date: '2023-08-04'
venue: 'ACM SIGGRAPH Asia 2023'
paperurl: 'https://dl.acm.org/doi/10.1145/3610548.3618181'
citation: "Hongyu Tao, Shuaiying Hou, Changqing Zou, Hujun Bao, and Weiwei Xu. 2023. Neural Motion Graph. In SIGGRAPH Asia 2023 Conference Papers (SA '23). Association for Computing Machinery, New York, NY, USA, Article 84, 1–11. https://doi.org/10.1145/3610548.3618181"
---

[Download paper here](https://dl.acm.org/doi/10.1145/3610548.3618181)

Hongyu Tao, [**Shuaiying Hou**](https://houericsy.github.io/ShuaiyingHou/), [Changqing Zou](https://changqingzou.weebly.com/), [Hujun Bao](http://www.cad.zju.edu.cn/home/bao/), [Weiwei Xu](http://www.cad.zju.edu.cn/home/weiweixu/weiweixu_en.htm)


**BibTeX**\
@inproceedings{10.1145/3610548.3618181,\
&emsp;author = {Tao, Hongyu and Hou, Shuaiying and Zou, Changqing and Bao, Hujun and Xu, Weiwei},\
&emsp;title = {Neural Motion Graph},\
&emsp;year = {2023},\
&emsp;isbn = {9798400703157},\
&emsp;publisher = {Association for Computing Machinery},\
&emsp;address = {New York, NY, USA},\
&emsp;url = {https://doi.org/10.1145/3610548.3618181},\
&emsp;doi = {10.1145/3610548.3618181},\
&emsp;booktitle = {SIGGRAPH Asia 2023 Conference Papers},\
&emsp;articleno = {84},\
&emsp;numpages = {11},\
&emsp;keywords = {generative model, motion graph, deep learning, human motion synthesis},\
&emsp;location = {Sydney, NSW, Australia},\
&emsp;series = {SA '23}\
}