# Loss-family

* Segmentation of Head and Neck Organs at Risk Using CNN with Batch Dice Loss [[paper](https://arxiv.org/pdf/1812.02427.pdf)]
* 3D Segmentation with Exponential Logarithmic Loss for Highly Unbalanced Object Sizes [[paper](https://arxiv.org/pdf/1809.00076.pdf)]
* Combating Uncertainty with Novel Losses for Automatic Left Atrium Segmentation [[paper](https://arxiv.org/pdf/1812.05807.pdf)]
* Generalised Wasserstein Dice Score for Imbalanced Multi-class Segmentation using Holistic Convolutional Networks [[paper](https://arxiv.org/pdf/1707.00478.pdf)]
* A NOVEL FOCAL TVERSKY LOSS FUNCTION WITH IMPROVED ATTENTION U-NET FOR LESION SEGMENTATION [[paper](https://arxiv.org/pdf/1810.07842.pdf)]
* Boundary loss for highly unbalanced segmentation [[paper](https://arxiv.org/pdf/1812.07032.pdf)]

## Lovász-Softmax loss

The Lovász-Softmax loss: A tractable surrogate for the optimization of the intersection-over-union measure in neural networks

### 相关链接

* 论文: https://arxiv.org/pdf/1705.08790.pdf
* 代码: https://github.com/bermanmaxim/LovaszSoftmax
* 相关参考：
  * 有关语义分割的奇技淫巧有哪些？ - AlexL的回答 - 知乎 https://www.zhihu.com/question/272988870/answer/562262315
  * CVPR 2018：用于图像分割网络的Lovasz loss学习笔记 - JunMa的文章 - 知乎 https://zhuanlan.zhihu.com/p/76825379

## Generalized Dice Loss

Generalised Dice overlap as a deep learning loss function for highly unbalanced segmentations

这篇文章介绍了数种针对不平衡分割数据的损失，包括weighted cross-entropy function，sensitivity function和Dice loss function，同时针对现有的the Generalized Dice Score进行扩展，提出了Generalized Dice Loss。

**Weighted cross-entropy (WCE)**

![](https://user-images.githubusercontent.com/26847524/63738226-b30e2900-c8bb-11e9-92f5-97fab4cf7fd0.png)

**Dice loss (DL)**

![](https://user-images.githubusercontent.com/26847524/63738238-bb666400-c8bb-11e9-9330-c73a239c05e2.png)

**Sensitivity - Specificity (SS)**

![](https://user-images.githubusercontent.com/26847524/63738255-c7522600-c8bb-11e9-8a88-52015bc93595.png)

**Generalized Dice Loss (GDL)**

![](https://user-images.githubusercontent.com/26847524/63738443-5e1ee280-c8bc-11e9-9d1e-3c8d2702032c.png)

### 相关链接

* 论文：https://arxiv.org/pdf/1707.03237.pdf
