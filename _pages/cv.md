---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Software Engineering, [Northwestern Polytechnical University](https://www.nwpu.edu.cn/), 2017
* Ph.D in Computer Science and Technology, [Zhejiang University](https://www.zju.edu.cn/), 2024 (expected)

Work experience
======
* 2018-07 to 2021-05: Research Intern
  * XMov, Shanghai
  * Duties included: Human segmentation algorithm developing and optimizing, human motion generation algorithm researching

* 2021-07 to 2023-01: Research Intern
  * Central Media Technology Institute, HUAWEI, Hangzhou
  * Duties included: Controllable limb movement generation project researching and developing
  
Skills
======
* Programming Language
  * Python
  * C++
  * C#
* Machine Learning Libirary
  * PyTorch
  * TensorFlow
  * Caffe
* Others
  * MotionBuilder
  * Unity 3D
  * OpenGL
  * Qt
  * Blender
  * Office

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    .hidden-info {
      display: none;
      position: absolute;
      background-color: #f9f9f9;
      border: 1px solid #ddd;
      padding: 10px;
      z-index: 1;
    }
  </style>
</head>
<body>

Publications
======
* [A causal convolutional neural network for multi-subject motion modeling and generation](https://link.springer.com/article/10.1007/s41095-022-0307-3)\
[**Shuaiying Hou**](https://houericsy.github.io/ShuaiyingHou/), Congyi Wang, Wenlin Zhuang, Yu Chen, [Yangang Wang](https://www.yangangwang.com/), [Hujun Bao](http://www.cad.zju.edu.cn/home/bao/), [Jinxiang Chai](https://scholar.google.com/citations?user=OcN1_gwAAAAJ&hl=zh-CN), [Weiwei Xu](http://www.cad.zju.edu.cn/home/weiweixu/weiweixu_en.htm)<span id="info-toggle">*</span>

* [A Two-part Transformer Network for Controllable Motion Synthesis](https://ieeexplore.ieee.org/document/10147861)\
[**Shuaiying Hou**](https://houericsy.github.io/ShuaiyingHou/), Hongyu Tao, [Hujun Bao](http://www.cad.zju.edu.cn/home/bao/), [Weiwei Xu](http://www.cad.zju.edu.cn/home/weiweixu/weiweixu_en.htm)<span id="info-toggle">*</span>

* [Neural Motion Graph](https://dl.acm.org/doi/10.1145/3610548.3618181)\
Hongyu Tao, [**Shuaiying Hou**](https://houericsy.github.io/ShuaiyingHou/), [Changqing Zou](https://changqingzou.weebly.com/), [Hujun Bao](http://www.cad.zju.edu.cn/home/bao/), [Weiwei Xu](http://www.cad.zju.edu.cn/home/weiweixu/weiweixu_en.htm)<span id="info-toggle">*</span>

<div id="corresponding-author" class="hidden-info">
  <p>通讯作者：详细信息在这里。</p>
</div>

<script>
  // 获取元素
  const toggleElement = document.getElementById('info-toggle');
  const infoElement = document.getElementById('corresponding-author');

  // 添加点击事件
  toggleElement.addEventListener('click', function() {
    // 切换显示和隐藏
    infoElement.style.display = (infoElement.style.display === 'none' || infoElement.style.display === '') ? 'block' : 'none';
  });
</script>

</body>
</html>

<!-- Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
