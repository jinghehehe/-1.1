# 视频目标检测

## 1.object detection。目前得出的结果都是基于RBG大神在13年所提出的开创性工作——R-CNN。
[R-CNN详解](https://zhuanlan.zhihu.com/p/22287237)

论文：Rich feature hierarchies for accurate object detection and semantic segmentation

## 2.Ross Girshick在15年推出Fast RCNN，构思精巧，流程更为紧凑——Fast RCNN
[Fast RCNN详解](https://blog.csdn.net/shenxiaolu1984/article/details/51036677)

[Fast RCNN代码](https://github.com/rbgirshick/fast-rcnn)（现已不再维护）

论文：Fast R-CNN - The Computer Vision Foundation

## 3.目标检测界的领军人物Ross Girshick团队在2015年的又一力作。Faster RCNN
[Faster RCNN详解](https://blog.csdn.net/shenxiaolu1984/article/details/51

论文：FasterR-CNN:Towards Real-Time Object Detection with Region Proposal Networks

## 4.YOLO(you only look once)是真正实现端到端的目标检测算法。
[YOLO详解](https://zhuanlan.zhihu.com/p/25045711)

[YOLO详解2](https://zhuanlan.zhihu.com/p/37668951)

[YOLO详解3](https://blog.csdn.net/Jesse_Mx/article/details/53925356)

[YOLO代码](https://github.com/pjreddie/darknet)

论文：YOLO v1 You Only Look Once: Unified, Real-Time Object Detection

论文：YOLO v2 YOLO9000: Better, Faster, Stronger 
     
论文：YOLO v3 YOLOv3: An Incremental Improvement
     
## 5.SSD是对Faster RCNN RPN这一独特步骤的延伸与整合
[SSD详解](https://blog.csdn.net/u014380165/article/details/72824889)

[SSD详解2](https://blog.csdn.net/smf0504/article/details/52745070)

[SSD代码](https://github.com/pjreddie/darknet)

论文：SSD: Single Shot MultiBox Detector

## 6.DSSD解决了 SSD 算法检测小目标困难的问题
[DSSD详解](https://blog.csdn.net/jesse_mx/article/details/55212179?utm_source=itdadao&utm_medium=referral)

[DSSD代码](https://github.com/chengyangfu/caffe/tree/dssd)

论文：DSSD : Deconvolutional Single Shot Detector 

## 7.T-CNN（树结构的CNN），是VOT2016的冠军
[T-CNN详解](https://blog.csdn.net/linolzhang/article/details/74999644)

[T-CNN代码](https://github.com/myfavouritekk/T-CNN)

论文：T-CNN: Tubelets with Convolutional Neural Networks for Object Detection from Videos

## 8.SPP-NET在最后一个卷积层后，接入了金字塔池化层，使用这种方式，可以让网络输入任意的图片，而且还会生成固定大小的输出。
[SPP-NET详解](https://blog.csdn.net/v1_vivian/article/details/73275259)

[SPP-NET代码](https://github.com/yueruchen/sppnet-pytorch)

论文：Spatial Pyramid Pooling in Deep ConvolutionalNetworks for Visual Recognition

## 9.Light Head RCNN是旷视和清华大学在COCO 2017比赛拿到冠军的算法
[Light Head RCNN详解](https://blog.csdn.net/Dlyldxwl/article/details/78714195)

[Light Head RCNN代码](https://github.com/zengarden/light_head_rcnn)

论文：Light-Head R-CNN: In Defense of Two-Stage Object Detector

## 10.R-FCN可以将ResNet等全卷积图片分类器转换为目标识别用。可以达到比faster rcnn快2.5-20倍。
[R-FCN详解](https://blog.csdn.net/bea_tree/article/details/51817263)

[R-FCN代码]( https://github.com/daijifeng001/R-FCN)

论文：R-FCN: Object Detection via Region-based Fully Convolutional Networks

![Alt text](https://github.com/jinghehehe/-1.1/blob/master/%E6%88%AA%E5%9B%BE/1.jpgg)
