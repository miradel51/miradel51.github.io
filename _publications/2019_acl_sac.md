---
title: "Soft Contextual Data Augmentation for Neural Machine Translation"
collection: publications
permalink: /publication/2019_acl_sac
excerpt: ''
date: 2019-07-28
author: Jinhua Zhu*, Fei Gao*, <b>Lijun Wu</b>, Yingce Xia, Tao Qin, Wengang Zhou, Xueqi Cheng, and Tie-Yan Liu
conference: In 57th Annual Meeting of the Association for Computational Linguistics <b>(ACL-2019)</b>  (*=equal contribution)
venue: ''
paperurl: 'https://www.aclweb.org/anthology/P19-1555.pdf'
citation: '<br>
@inproceedings{gao2019soft,<br>
  title={Soft contextual data augmentation for neural machine translation},<br>
  author={Gao, Fei and Zhu, Jinhua and Wu, Lijun and Xia, Yingce and Qin, Tao and Cheng, Xueqi and Zhou, Wengang and Liu, Tie-Yan},<br>
  booktitle={Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics},<br>
  pages={5539--5544},<br>
  year={2019}<br>
}'

---
<h2><strong>Abstract</strong></h2>
While data augmentation is an important trickto boost the accuracy of deep learning methods in computer vision tasks, its study in natural  language  tasks  is  still  very  limited.  In this paper,  we present a novel  data augmentation method for neural machine translation.Different from previous augmentation  methods that randomly drop, swap or replace words with other words in a sentence, we softly augment a randomly chosen word in a sentence by  its contextual mixture of multiple related words. More accurately, we replace the one-hot  representation of a word by a distribution (provided by a language model) over the vocabulary, i.e., replacing the embedding of this wordby a weighted combination of multiple semantically similar  words.  Since the weights of those words depend on the contextual information of the word to be replaced, the newly generated sentences capture much richer  information than previous augmentation methods. Experimental results on both small scale  and large scale machine translation datasets demonstrate the superiority of ourmethod over strong baselines.

\[[PDF](https://www.aclweb.org/anthology/P19-1555.pdf)\]  \[[CODE](https://github.com/teslacool/lm_fairseq)\]