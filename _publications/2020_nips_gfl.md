---
title: "Generalized Focal Loss: Learning Qualified and Distributed Bounding Boxes for Dense Object Detection"
collection: publications
permalink: /publication/2020_nips_gfl
excerpt: ''
date: 2020-09-25
author: Xiang Li, Wenhai Wang, <b>Lijun Wu</b>, Shuo Chen, Xiaolin Hu, Jun Li, Jinhui Tang, Jian Yang
conference: In 34th Conference on Neural Information Processing Systems <b>(NeurIPS-2020)</b>
venue: ''
paperurl: ''
citation: '<br>
@inproceedings{li2020generalized,<br>
  title={Generalized Focal Loss: Learning Qualified and Distributed Bounding Boxes for Dense Object Detection},<br>
  author={Li, Xiang and Wang, Wenhai and Wu, Lijun and Chen, Shuo and Hu, Xiaolin and Li, Jun and Tang, Jinhui and Yang, Jian},<br>
  booktitle={Advances in Neural Information Processing Systems},<br>
  year={2020}<br>
}'

---
<h2><strong>Abstract</strong></h2>
One-stage detector basically formulates object detection as dense classification and localization (i.e., bounding box regression). The classification is usually optimized by Focal Loss and the box location is commonly learned under Dirac delta distribution. A recent trend for one-stage detectors is to introduce an individual prediction branch to estimate the quality of localization, where the predicted quality facilitates the classification to improve detection performance. This paper delves into the representations of the above three fundamental elements: quality estimation, classification and localization. Two problems are discovered in existing practices, including (1) the inconsistent usage of the quality estimation and classification between training and inference (i.e., separately trained but compositely used in test) and (2) the inflexible Dirac delta distribution for localization when there is ambiguity and uncertainty which is often the case in complex scenes. To address the problems, we design new representations for these elements. Specifically, we merge the quality estimation into the class prediction vector to form a joint representation of localization quality and classification, and use a vector to represent arbitrary distribution of box locations. The improved representations eliminate the inconsistency risk and accurately depict the flexible distribution in real data, but contain continuous labels, which is beyond the scope of Focal Loss. We then propose Generalized Focal Loss (GFL) that generalizes Focal Loss from its discrete form to the continuous version for successful optimization. On COCO test-dev, GFL achieves 45.0% AP using ResNet-101 backbone, surpassing state-of-the-art SAPD (43.5%) and ATSS (43.6%) with higher or comparable inference speed, under the same backbone and training settings. Notably, our best model can achieve a single-model single-scale AP of 48.2%, at 10 FPS on a single 2080Ti GPU. Code and pretrained models are available at https://github.com/implus/GFocal.

\[[PDF](https://arxiv.org/pdf/2006.04388.pdf)\]  \[[CODE](https://github.com/implus/GFocal)\]