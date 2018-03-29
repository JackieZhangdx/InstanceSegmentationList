# Instance Semantic Segmentation List

This repository contains lists of state-or-art instance semantic segmentation works. Papers and resources are listed below according to method types.

- [x] Paper list
	- [x] detection based
	- [x] segmentation based


#### Brief introduction
Instance semantic segmentation is a area closely related to detection and semantic segmentation. In particular, it could be seen as *detection plus foreground mask*. But mostly it is not able to segment non-object pixels such as sky, land etc(which considered as a scene parsing task under semantic segmentation). For quick review related topics, see these survey papers: 

[Speed/accuracy trade-offs for modern convolutional object detectors](https://arxiv.org/abs/1611.10012), CVPR 2017

[Survey of recent progress in semantic image segmentation with CNNs](https://link.springer.com/article/10.1007/s11432-017-9189-6), until 201706

<h2 id="1">1.Detection-based methods</h2>

* [PAnet:Path Aggregation Network for Instance Segmentation](https://arxiv.org/pdf/1803.01534.pdf), CVPR 2018

* [Mask R-CNN](https://arxiv.org/abs/1703.06870), ICCV 2017  \[[Detectron](https://github.com/facebookresearch/Detectron)\]\[[Code(TF)](https://github.com/matterport/Mask_RCNN)\]\[[Code(MXNET)](https://github.com/TuSimple/mx-maskrcnn)\]

* [BlitzNet: A Real-Time Deep Network for Scene Understanding](https://arxiv.org/abs/1708.02813), ICCV 2017 \[[web](http://thoth.inrialpes.fr/research/blitznet/)\]\[[code](https://github.com/dvornikita/blitznet)\]

* [MaskLab: Instance Segmentation by Refining Object Detection with Semantic and Direction Features](https://arxiv.org/abs/1712.04837) Arxiv1712 

* [FCIS: Fully Convolutional Instance-Aware Semantic Segmentation](https://arxiv.org/abs/1611.07709), CVPR 2017 \[[code](https://github.com/msracver/FCIS)\]

* [FastMask: Segment Multi-scale Object Candidates in One Shot](https://arxiv.org/abs/1612.08843), CVPR 2017 \[[code](https://github.com/voidrank/FastMask)\]

* [instance sensitive fully convolutional networks](https://arxiv.org/abs/1603.08678), ECCV 2016 

* [MNC: Instance-aware Semantic Segmentation via Multi-task Network Cascades](https://arxiv.org/abs/1512.04412), CVPR 2016 \[[code](https://github.com/daijifeng001/MNC)\]

* [SharpMask: Learning to Refine Object Segments](https://arxiv.org/abs/1603.08695), ECCV 2016

* [DeepMask: Learning to Segment Object Candidates](https://arxiv.org/abs/1506.06204), NIPS 2015 \[[code](https://github.com/facebookresearch/deepmask)\]

<h2 id="2">2.Segmentation-based methods</h2>

* [SGN: Sequential Grouping Networks for Instance Segmentation](http://www.cs.toronto.edu/~urtasun/publications/liu_etal_iccv17.pdf), ICCV 2017

* [InstanceCut: from Edges to Instances with MultiCut](https://arxiv.org/abs/1611.08272),CVPR 2017

* [Pixelwise Instance Segmentation with a Dynamically Instantiated Network](https://arxiv.org/abs/1704.02386), CVPR 2017

* [Deep Watershed Transform for Instance Segmentation](https://arxiv.org/abs/1611.08303), CVPR 2017 \[[code](https://github.com/min2209/dwt)\]

* [Multi-scale Patch Aggregation (MPA) for Simultaneous Detection and Segmentation](http://www.cse.cuhk.edu.hk/leojia/papers/mpa_cvpr16.pdf), CVPR 2016

<h2 id="3">3.Others</h2>

* [End-to-End Instance Segmentation with Recurrent Attention](https://arxiv.org/abs/1605.09410), CVPR 2017 

* [Recurrent Instance Segmentation](https://arxiv.org/abs/1511.08250), ECCV 2016 \[[web](https://github.com/bernard24/RIS)\]

* [SDS:Simultaneous Detection and Segmentation](https://arxiv.org/abs/1407.1808), ECCV 2014 \[[web](https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/shape/sds/)\] \[[code](https://github.com/bharath272/sds_eccv2014)\]

* [Hypercolumns for Object Segmentation and Fine-grained Localization](https://arxiv.org/abs/1411.5752) , CVPR 2015
