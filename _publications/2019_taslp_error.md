---
title: "Beyond Error Propagation in Neural Machine Translation: Characteristics of Language Also Matter"
collection: publications
permalink: /publication/2019_taslp_error
excerpt: ''
date: 2019-08-07
author: <b>Lijun Wu</b>, Xu Tan, Tao Qin, Jianhuang Lai and Tie-Yan Liu
conference: In IEEE/ACM Transactions on Audio, Speech and Language Processing <b>(IEEE/ACM TASLP, 2019)</b>
venue: ''
paperurl: 'https://ieeexplore.ieee.org/abstract/document/8790778'
citation: '<br>
@article{wu2019beyond,<br>
  title={Beyond Error Propagation: Language Branching Also Affects the Accuracy of Sequence Generation},<br>
  author={Wu, Lijun and Tan, Xu and Qin, Tao and Lai, Jianhuang and Liu, Tie-Yan},<br>
  journal={IEEE/ACM Transactions on Audio, Speech, and Language Processing},<br>
  volume={27},<br>
  number={12},<br>
  pages={1868--1879},<br>
  year={2019},<br>
  publisher={IEEE}<br>
}'

---
<h2><strong>Abstract</strong></h2>
Sequence generation tasks, such as neural machine translation (NMT) and abstractive summarization, usually suffer from exposure bias as well as the error propagation problem due to the autoregressive training and generation. Many previous works have discussed the relationship between error propagation and the accuracy drop problem (i.e., the right part of the generated sentence is often worse than its left part in left-to-right decoding models). In this paper, taking NMT as a typical sequence generation task, we measure the accuracy of the generated sentence with various metrics and conduct a series of analyses to deeply understand the accuracy drop problem. We obtain several interesting findings. First, The role of error propagation on accuracy drop is overstated in the literature, although it is indeed a cause to the accuracy drop problem. Second, Characteristics of a language play a more important role in causing the accuracy drop problem: the left part of the generated sentence in a right-branching language (e.g., English) is more likely to be more accurate than its right part, while the right part is more accurate for a left-branching language (e.g., Japanese). Our discoveries are also confirmed on other generation tasks (e.g., image captioning, abstractive summarization and language modeling) with multiple left/right-branching languages, as well as in various model structures.

\[[PDF](https://ieeexplore.ieee.org/abstract/document/8790778)\]  