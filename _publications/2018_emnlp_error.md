---
title: "Beyond Error Propagation in Neural Machine Translation: Characteristics of Language Also Matter"
collection: publications
permalink: /publication/2018_emnlp_error
excerpt: ''
date: 2018-10-31
author: <b>Lijun Wu</b>*, Xu Tan*, Di He, Fei Tian, Tao Qin, Jianhuang Lai and Tie-Yan Liu
conference: In 2018 Conference on Empirical Methods in Natural Language Processing <b>(EMNLP-2018)</b>  (*=equal contribution)
venue: ''
paperurl: 'https://www.aclweb.org/anthology/D18-1396.pdf'
citation: '<br>
@inproceedings{wu2018beyond,<br>
  title={Beyond Error Propagation in Neural Machine Translation: Characteristics of Language Also Matter},<br>
  author={Wu, Lijun and Tan, Xu and He, Di and Tian, Fei and Qin, Tao and Lai, Jianhuang and Liu, Tie-Yan},<br>
  booktitle={Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing},<br>
  pages={3602--3611},<br>
  year={2018}<br>
}'

---
<h2><strong>Abstract</strong></h2>
Neural machine translation usually adopts autoregressive models and suffers from exposure bias as well as the consequent error propagation problem. Many previous works have discussed the relationship between error propagation and the accuracy drop (i.e., the left part of the translated sentence is often better than its right part in left-to-right decoding models) problem. In this paper, we conduct a series of analyses to deeply understand this problem and get several interesting findings. (1) The role of error propagation on accuracy drop is overstated in the literature, although it indeed contributes to the accuracy drop problem. (2) Characteristics of a language play a more important role in causing the accuracy drop: the left part of the translation result in a right-branching language (e.g., English) is more likely to be more accurate than its right part, while the right part is more accurate for a left-branching language (e.g., Japanese). Our discoveries are confirmed on different model structures including Transformer and RNN, and in other sequence generation tasks such as text summarization.

\[[PDF](https://www.aclweb.org/anthology/D18-1396.pdf)\]  