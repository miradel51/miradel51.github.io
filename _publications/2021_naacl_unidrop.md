---
title: "UniDrop: A Simple yet Effective Technique to Improve Transformer without Extra Cost"
collection: publications
permalink: /publication/2021_naacl_unidrop
excerpt: ''
date: 2021-06-06
author: Zhen Wu, <b>Lijun Wu</b>, Qi Meng, Yingce Xia, Shufang Xie, Tao Qin, Xinyu Dai and Tie-Yan Liu
conference: In The 2021 Conference of the North American Chapter of the Association for Computational Linguistics - Human Language Technologies <b>(NAACL-2021) </b>
venue: ''
paperurl: ''
citation: '<br>
@inproceedings{wu2021unidrop,<br>
  title={UniDrop: A Simple yet Effective Technique to Improve Transformer without Extra Cost},<br>
  author={Wu, Zhen and Wu, Lijun and Qi, Meng and Xia, Yingce and Xie, Shufang and Qin, Tao and Dai, Xinyu and Liu, Tie-Yan},<br>
  booktitle={Proceedings of the The 2021 Conference of the North American Chapter of the Association for Computational Linguistics - Human Language Technologies, <br> Volume 1 (Long Papers)},<br>
  year={2021}<br>
}'

---
<h2><strong>Abstract</strong></h2>
Transformer architecture achieves great success in abundant natural language processing tasks. The over-parameterization of the Transformer model has motivated plenty of works to alleviate its overfitting for superior performances. With some explorations, we find simple techniques such as dropout, can greatly boost model performance with a careful design. Therefore, in this paper, we integrate different dropout techniques into the training of Transformer models. Specifically, we propose an approach named $\mathtt{UniDrop}$ to unites three different dropout techniques from fine-grain to coarse-grain, i.e., feature dropout, structure dropout, and data dropout. Theoretically, we demonstrate that these three dropouts play different roles from regularization perspectives. Empirically, we conduct experiments on both neural machine translation and text classification benchmark datasets. Extensive results indicate that Transformer with $\mathtt{UniDrop}$ can achieve around $1.5$ BLEU improvement on IWSLT14 translation tasks, and better accuracy for the classification even using strong pre-trained RoBERTa as backbone.


\[[PDF]()\]  