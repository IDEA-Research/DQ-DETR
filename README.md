# DQ-DETR

This is the official pytorch implementation of our AAAI 2023 paper DQ-DETR. Code will be available soon!

Authors: [Shilong Liu](https://www.lsl.zone/), [Yaoyuan Liang](https://scholar.google.com/citations?user=n47YI20AAAAJ&hl=zh-CN), [Feng Li](https://scholar.google.com/citations?hl=zh-CN&user=ybRe9GcAAAAJ), [Shijia Huang](https://sega-hsj.github.io/), [Hao Zhang](https://scholar.google.com/citations?user=B8hPxMQAAAAJ&hl=zh-CN), [Hang Su](https://www.suhangss.me/), [Jun Zhu](https://ml.cs.tsinghua.edu.cn/~jun/index.shtml), [Lei Zhang](https://www.leizhang.org/)

## phrase extraction and grounding(PEG)
PEG requires a model to extract phrases from text and locate objects from image simultaneously. As phrase extraction can be regarded as a 1D text segmentation problem, we formulate PEG as a dual detection problem. 


![tasks_comparison](.asset\tasks_comparison.png)



To evaluate the performance of PEG, we also propose a new metric CMAP (cross-modal average precision), analogous to the AP metric in object detection.

![cmap](.asset\cmap.png)




## DQ-DETR
As phrase extraction can be regarded as a 1D text segmentation problem, we formulate PEG as a dual detection problem.

![dq-detr](.asset\dq-detr.png)

## Experiments

![refcoco](.asset\refcoco.png)
![flickr30k](.asset\flickr30k.png)

