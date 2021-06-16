---
title: "Sequence Generation with Mixed Representations"
collection: publications
permalink: /publication/2020_icml_mix_rep
excerpt: ''
date: 2020-07-12
author: <b>Lijun Wu</b>, Shufang Xie, Yingce Xia, Yang Fan, Tao Qin, Jianhuang Lai, Tie-Yan Liu
conference: In Thirty-seventh International Conference on Machine Learning <b>(ICML-2020)</b>
venue: ''
paperurl: ''
citation: '<br>
@inproceedings{wu2020seqgenmix,<br>
  title={Sequence Generation with Mixed Representations},<br>
  author={Wu, Lijun and Xie, Shufang and Xia, Yingce and Fan, Yang ad=nd Qin, Tao and Zhou, Wengang and Li, Houqiang and Liu, Tie-Yan},<br>
  booktitle={International Conference on Machine Learning},<br>
  year={2020}<br>
}'

---
<h2><strong>Abstract</strong></h2>
Tokenization is the first step of many natural language processing (NLP) tasks and plays an important role for neural NLP models. Tokenization methods such as byte-pair encoding and SentencePiece, which can greatly reduce the large vocabulary size and deal with out-of-vocabulary words, have shown to be effective and are widely adopted for sequence generation tasks. While various tokenization methods exist, there is no common acknowledgement which one is the best. In this work, we propose to leverage the mixed representations from different tokenizers for sequence generation tasks, which can take the advantages of each individual tokenization method.
Specifically, we introduce a new model architecture to incorporate mixed representations and a co-teaching algorithm to better utilize the diversity of different tokenization methods. Our approach achieves significant improvements on neural machine translation tasks with six language pairs, as well as an abstractive summarization task.

\[[PDF](https://proceedings.icml.cc/static/paper_files/icml/2020/3729-Paper.pdf)\]  \[[CODE](https://github.com/apeterswu/fairseq_mix)\]