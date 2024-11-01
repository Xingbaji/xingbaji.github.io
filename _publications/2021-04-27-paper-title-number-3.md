---
title: "Dct-mask: Discrete cosine transform mask representation for instance segmentation"
collection: publications
permalink: /publication/DCT-Mask
excerpt: 'Binary grid mask representation is broadly used in instance segmentation. A representative instantiation is Mask R-CNN which predicts masks on a 28* 28 binary grid. Generally, a low-resolution grid is not sufficient to capture the details, while a high-resolution grid dramatically increases the training complexity. In this paper, we propose a new mask representation by applying the discrete cosine transform (DCT) to encode the high-resolution binary grid mask into a compact vector. Our method, termed DCT-Mask, could be easily integrated into most pixel-based instance segmentation methods. Without any bells and whistles, DCT-Mask yields significant gains on different frameworks, backbones, datasets, and training schedules. It does not require any pre-processing or pre-training, and almost no harm to the running speed. Especially, for higher-quality annotations and more complex backbones, our method has a greater improvement. Moreover, we analyze the performance of our method from the perspective of the quality of mask representation. The main reason why DCT-Mask works well is that it obtains a high-quality mask representation with low complexity.'
date: 2021-04-27
venue: 'CVPR2021(oral)'
paperurl: 'https://github.com/aliyun/DCT-Mask'
---

[Download paper here](http://xingbaji.github.io/files/DCT_Mask.pdf)
