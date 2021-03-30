## Paper List

### 1. Image Classification

|                            paper                             | description                                                  |                     good notes shareing                      | year      |                           github                            |
| :----------------------------------------------------------: | ------------------------------------------------------------ | :----------------------------------------------------------: | --------- | :---------------------------------------------------------: |
| [__EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks__](https://arxiv.org/abs/1905.11946) | __Balance three dimensions of ConvNets, e.g.,  depth, width and resolution__ |                             ...                              | 2019      | [github](https://github.com/lukemelas/EfficientNet-PyTorch) |
| [__MnasNet: Platform-Aware Neural Architecture Search for Mobile__](https://openaccess.thecvf.com/content_CVPR_2019/papers/Tan_MnasNet_Platform-Aware_Neural_Architecture_Search_for_Mobile_CVPR_2019_paper.pdf) | 针对移动端网络设计的Nas方法，设计出表现好，效率高的Net   | [__MNasNet论文笔记__](https://zhuanlan.zhihu.com/p/103802311) | CVPR 2019 |                                                             |
| [__Coordinate Attention for Efficient Mobile Network Design__](https://arxiv.org/abs/2103.02907) | 考虑channel attention的同时融入position attention            |                                                              | CVPR 2021 |  [github](https://github.com/Andrew-Qibin/CoordAttention)   |
| [__MobileNetV2: Inverted Residuals and Linear Bottlenecks__](https://arxiv.org/abs/1801.04381) | 重新思考了ReLU带来的数据流失影响，并重新设计了纺锤型的bottleneck模块            |           [__ResNet的本质思考__](https://zhuanlan.zhihu.com/p/60668529)   | Arxiv 2018 |  [github](https://github.com/tonylins/pytorch-mobilenet-v2)   |
| [__RexNet: Dinimishing Representational Bottleneck on Convolutional Neural Network__](https://arxiv.org/abs/2007.00992) | 通过矩阵秩的角度分析模型的表达瓶颈，重新思考了模型结构设计，并达到了超越EfficientNet的分类性能结果            |           ...   | CVPR 2021 |  [github](https://github.com/clovaai/rexnet)   |
| [__Stand-Alone Self-Attention in Vision Models__](https://arxiv.org/abs/1906.05909) | 尝试使用attention替换掉卷积操作，设计了full-attention的网络结构，是attention完全替换卷积的第一次尝试            |           ...   | NIPS 2019 |  [github](https://github.com/leaderj1001/Stand-Alone-Self-Attention)   |


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
| [__Searching for Activation Functions__](https://arxiv.org/abs/1710.05941) | __Swish Activation Function__ |[searching for activation functions](https://medium.com/@chia.sheng.chen/6-searching-for-activation-functions-14a3f89b5351)| Arxiv 2017| ... |


