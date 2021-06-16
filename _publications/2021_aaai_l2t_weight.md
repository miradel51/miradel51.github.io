---
title: "Learning to Reweight with Deep Interactions"
collection: publications
permalink: /publication/2021_aaai_l2t_weight
excerpt: ''
date: 2021-02-02
author: Yang Fan, Yingce Xia, <b>Lijun Wu</b>, Shufang Xie, Weiqing Liu, Jiang Bian, Xiangyang Li, Tao Qin
conference: In Thirty-Fifth AAAI Conference on Artificial Intelligence <b>(AAAI-2021)</b>
venue: ''
paperurl: 'https://arxiv.org/pdf/2007.04649.pdf'
citation: '<br>
@inproceedings{Fan2021learn,<br>
  title={TLearning to Reweight with Deep Interactions},<br>
  author={Fan, Yang and Xia, Yingce and Wu, Lijun and Xie, Shufang and Liu, Weiqing and Bian, Jiang and Qin, Tao},<br>
  booktitle={AAAI},<br>
  year={2021}<br>
}'

---
<h2><strong>Abstract</strong></h2>
Machine teaching uses a meta/teacher model to guide the training of a student model (which will be used in real tasks) through training data selection, loss function design, etc. Previously, the teacher model only takes shallow/surface information as inputs (e.g., training iteration number, loss and accuracy from training/validation sets) while ignoring the internal states of the student model, which limits the potential of learning to teach. In this work, we propose an improved data teaching algorithm, where the teacher model deeply interacts with the student model by accessing its internal states. The teacher model is jointly trained with the student model using meta gradients propagated from a validation set. We conduct experiments on image classification with clean/noisy labels and empirically demonstrate that our algorithm makes significant improvement over previous data teaching methods.

\[[PDF](https://arxiv.org/pdf/2007.04649.pdf)\]  
