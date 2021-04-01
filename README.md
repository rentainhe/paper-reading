## Paper List

### 1. Image Classification

|                            paper                             | description                                                  |                     good notes shareing                      | year      |                           github                            |
| :----------------------------------------------------------: | ------------------------------------------------------------ | :----------------------------------------------------------: | --------- | :---------------------------------------------------------: |
| [__EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks__](https://arxiv.org/abs/1905.11946) | __Balance three dimensions of ConvNets, e.g.,  depth, width and resolution__ |                             ...                              | 2019      | [github](https://github.com/lukemelas/EfficientNet-PyTorch) |
| [__MnasNet: Platform-Aware Neural Architecture Search for Mobile__](https://openaccess.thecvf.com/content_CVPR_2019/papers/Tan_MnasNet_Platform-Aware_Neural_Architecture_Search_for_Mobile_CVPR_2019_paper.pdf) | __针对移动端网络设计的Nas方法，设计出表现好，效率高的Net__   | [__MNasNet论文笔记__](https://zhuanlan.zhihu.com/p/103802311) | CVPR 2019 |                            ...                                 |
| [__Coordinate Attention for Efficient Mobile Network Design__](https://arxiv.org/abs/2103.02907) | __考虑channel attention的同时融入position attention__            |                                   ...                           | CVPR 2021 |  [github](https://github.com/Andrew-Qibin/CoordAttention)   |
| [__MobileNetV2: Inverted Residuals and Linear Bottlenecks__](https://arxiv.org/abs/1801.04381) | __重新思考了ReLU带来的数据流失影响，并重新设计了纺锤型的bottleneck模块__            |           [__ResNet的本质思考__](https://zhuanlan.zhihu.com/p/60668529)   | Arxiv 2018 |  [github](https://github.com/tonylins/pytorch-mobilenet-v2)   |
| [__RexNet: Dinimishing Representational Bottleneck on Convolutional Neural Network__](https://arxiv.org/abs/2007.00992) | __通过矩阵秩的角度分析模型的表达瓶颈，重新思考了模型结构设计，并达到了超越EfficientNet的分类性能结果__            |           ...   | CVPR 2021 |  [github](https://github.com/clovaai/rexnet)   |
| [__Stand-Alone Self-Attention in Vision Models__](https://arxiv.org/abs/1906.05909) | __尝试使用attention替换掉卷积操作，设计了full-attention的网络结构，是attention完全替换卷积的第一次尝试__            |           ...   | NIPS 2019 |  [github](https://github.com/leaderj1001/Stand-Alone-Self-Attention)   |


### 2. Object Detection
|                            paper                             | description                                                  |                     good notes shareing                      | year      |                           github                            |
| :----------------------------------------------------------: | ------------------------------------------------------------ | :----------------------------------------------------------: | --------- | :---------------------------------------------------------: |
| [__End-to-End Object Detection with Transformers__](https://arxiv.org/abs/2005.12872) | __1. remove hand-designed components like NMS and Anchors  2. Use Transformer in detection__ |[DETR](https://xmuxg.xmu.edu.cn/xmu/app/214) <br> [匈牙利算法](https://zhuanlan.zhihu.com/p/96229700)| ECCV 2020| [github](https://github.com/facebookresearch/detr) |

### 3. Transformer
|                            paper                             | description                                                  |                     good notes shareing                      | year      |                           github                            |
| :----------------------------------------------------------: | ------------------------------------------------------------ | :----------------------------------------------------------: | --------- | :---------------------------------------------------------: |
| [__Self-Attention with Relative Position Representations__](https://arxiv.org/abs/1803.02155) | __use relative position embedding instead of absolute poesition embedding__ |[Transformer中加入相对位置信息](https://www.cnblogs.com/d0main/p/10453903.html)| NAACL 2018| ... |

### 4. Others
|                            paper                             | description                                                  |                     good notes shareing                      | year      |                           github                            |
| :----------------------------------------------------------: | ------------------------------------------------------------ | :----------------------------------------------------------: | --------- | :---------------------------------------------------------: |
| [__Searching for Activation Functions__](https://arxiv.org/abs/1710.05941) | __Swish Activation Function__ |[searching for activation functions](https://medium.com/@chia.sheng.chen/6-searching-for-activation-functions-14a3f89b5351)| Arxiv 2017 | ... |
| [__How much Position Information Do Convolutional Neural Networks Encode?__](https://openreview.net/forum?id=rJeB36NKvB) | __探究CNN是如何进行编码位置信息的, 结论发现CNN中的padding对于位置信息编码有重大作用__ |[图片中的绝对位置信息，CNN能搞定吗？](https://zhuanlan.zhihu.com/p/114713444)| ICLR 2020 | ... |

### 5. Classic Network and Method
|paper|description|good notes shareing| year | github |
| :---: | --- | :---: | --- | :---: |
| [__Learning Deep Features for Discriminative Localization__](https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Zhou_Learning_Deep_Features_CVPR_2016_paper.html) | __CAM: 关于CNN的可视化研究，取特征图加权和来可视化feature map，可视化解释CNN重点关注的区域__|[CAM和Grad-CAM篇](https://bindog.github.io/blog/2018/02/10/model-explanation/)|CVPR 2016| ... |
| [__Grad-CAM: Visual Explanations From Deep Networks via Gradient-Based Localization__](https://openaccess.thecvf.com/content_iccv_2017/html/Selvaraju_Grad-CAM_Visual_Explanations_ICCV_2017_paper.html) | __Grad-CAM: 进一步改进了CAM__| ... |ICCV 2017| ... |


