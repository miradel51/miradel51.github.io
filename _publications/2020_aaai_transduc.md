---
title: "Transductive Ensemble Learning for Neural Machine Translation"
collection: publications
permalink: /publication/2020_aaai_transduct
excerpt: ''
date: 2020-02-04
author: Yiren Wang*, <b>Lijun Wu</b>*, Yingce Xia, Tao Qin, Chengxiang Zhai, Tie-Yan Liu
conference: In Thirty-Fourth AAAI Conference on Artificial Intelligence <b>(AAAI-2020)</b> (*=equal contribution)
venue: ''
paperurl: 'https://www.aaai.org/Papers/AAAI/2020GB/AAAI-WangY.3465.pdf'
citation: '<br>
@inproceedings{wang2020transductive,<br>
  title={Transductive Ensemble Learning for Neural Machine Translation.},<br>
  author={Wang, Yiren and Wu, Lijun and Xia, Yingce and Qin, Tao and Zhai, ChengXiang and Liu, Tie-Yan},<br>
  booktitle={AAAI},<br>
  pages={6291--6298},<br>
  year={2020}<br>
}'

---
<h2><strong>Abstract</strong></h2>
Ensemble learning, which aggregates multiple diverse models for inference, is a common practice to improve the accuracy of machine learning tasks. However, it has been observedthat the conventional ensemble methods only bring marginal improvement for neural machine translation (NMT) when individual models are strong or there are a large number of individual models. In this paper, we study how to effectively aggregate multiple NMT models under the transductive settingwhere the source sentences of the test set are known. We propose a simple yet effective approach named transductive ensemble learning (TEL), in which we use all individual modelsto translate the source test set into the target language spaceand then finetune a strong model on the translated synthetic corpus. We conduct extensive experiments on different settings (with/without monolingual data) and different languagepairs (English↔{German, Finnish}). The results show thatour approach boosts strong individual models with significantimprovement and benefits a lot from more individual models.Specifically, we achieve the state-of-the-art performances onthe WMT2016-2018English↔German translations

\[[PDF](https://www.msra.cn/wp-content/uploads/2020/01/Transductive-Ensemble-Learning-for-Neural-Machine-Translation.pdf)\]  