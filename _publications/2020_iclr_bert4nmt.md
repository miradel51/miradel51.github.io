---
title: "Incorporating BERT into Neural Machine Translation"
collection: publications
permalink: /publication/2020_iclr_bert4nmt
excerpt: ''
date: 2020-04-26
author: Jinhua Zhu, Yingce Xia, <b>Lijun Wu</b>, Di He, Tao Qin, Wengang Zhou, Houqiang Li, Tie-Yan Liu
conference: In Eighth International Conference on Learning Representations <b>(ICLR-2020)</b>
venue: ''
paperurl: 'https://openreview.net/pdf?id=Hyl7ygStwB'
citation: '<br>
@inproceedings{zhu2020incorporating,<br>
  title={Incorporating BERT into Neural Machine Translation},<br>
  author={Zhu, Jinhua and Xia, Yingce and Wu, Lijun and He, Di and Qin, Tao and Zhou, Wengang and Li, Houqiang and Liu, Tie-Yan},<br>
  booktitle={International Conference on Learning Representations},<br>
  year={2020}<br>
}'

---
<h2><strong>Abstract</strong></h2>
The recently proposed BERT (Devlin et al., 2019) has shown great power on a variety of natural language understanding tasks, such as text classification, reading comprehension, etc. However, how to effectively apply BERT to neural machine translation (NMT) lacks enough exploration. While BERT is more commonly used as fine-tuning instead of contextual embedding for downstream language understanding tasks, in NMT, our preliminary exploration of using BERT as contextual embedding is better than using for fine-tuning. This motivates us to think how to better leverage BERT for NMT along this direction. We propose a new algorithm named BERT-fused model, in which we first use BERT to extract representations for an input sequence, and then the representations are fused with each layer of the encoder and decoder of the NMT model through attention mechanisms. We conduct experiments on supervised (including sentence-level and document-level translations), semi-supervised and unsupervised machine translation, and achieve state-of-the-art results on seven benchmark datasets. Our code is available at https://github.com/bert-nmt/bert-nmt.

\[[PDF](https://openreview.net/pdf?id=Hyl7ygStwB)\]  \[[CODE](https://github.com/bert-nmt/bert-nmt)\]