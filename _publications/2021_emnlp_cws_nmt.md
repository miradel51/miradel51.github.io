---
title: "Segment, Mask, and Predict: Augmenting Chinese Word Segmentation with Self-Supervision"
collection: publications
permalink: /publication/2021_emnlp_cws_nmt
excerpt: ''
date: 2021-08-26
author: <b>Mieradilijiang Maimaiti</b>, Yang Liu*, Yuanhang Zheng, Gang Chen, Kaiyu Huang, Ji Zhang, Huanbo Luan and Maosong Sun
conference: In International Conference on Empirical Methods in Natural Language Processing <b>(EMNLP, 2021)</b> (*=corresponding author) (Long paper, oral)
venue: ''
paperurl: 'https://2021.emnlp.org/'
citation: '<br>
@article{m.maimaiti_cws_EMNLP_2021,<br>
  title={Segment, Mask, and Predict: Augmenting Chinese Word Segmentation with Self-Supervision},<br>
  author={Maimaiti, Mieradilijiang and Liu, Yang and Zheng, Yuanhang and Chen, Gang and Huang, Kaiyu and Zhang,Ji and Luan, Huanbo and Sun, Maosong},<br>
  journal={International Conference on Empirical Methods in Natural Language Processing (EMNLP)},<br>
  year={2021},<br>
}'

---
<h2><strong>Abstract</strong></h2>
Recent state-of-the-art (SOTA) effective neural network methods and fine-tuning methods based on pre-trained models (PTM) have been used in Chinese word segmentation (CWS),
and they achieve great results. However, previous works focus on training the models with the fixed corpus at every iteration. The intermediate generated information is also valuable.
Besides, the robustness of the previous neuralmethods is limited by the large-scale annotated data. There are a few noises in the annotated corpus. Limited efforts have been made by pre013
vious studies to deal with such problems. In this work, we propose a self-supervised CWS approach with a straightforward and effective architecture. 
First, we train a word segmentation model and use it to generate the segmentation results. 
Then, we use a revised masked language model (MLM) to evaluate the quality of the segmentation results based on the predictions of the MLM. 
Finally, we leverage the evaluations to aid the training of the segmenter by improved minimum risk training. 
Experimental results show that our approach outperforms previous methods on 9 different CWS datasets with single criterion training and multiple criteria training and achieves better robustness.

\[[PDF](https://miradel51.github.io/files/emnlp2021_cws.pdf)\]\[[Code](https://github.com/miradel51/Self_Supervised_CWS)\]\[[Blog](https://thumtblog.github.io/2021/09/20/cws-mask-predict/)\]\[[Poster](https://miradel51.github.io/files/emnlp2021_me_poster.pdf)\]\[[Slides](https://miradel51.github.io/files/emnlp2021_oral_final_new.pdf)\]
