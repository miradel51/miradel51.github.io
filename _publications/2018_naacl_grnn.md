---
title: "Efficient Sequence Learning with Group Recurrent Networks"
collection: publications
permalink: /publication/2018_naacl_grnn
excerpt: ''
date: 2018-06-01
author: Fei Gao, <b>Lijun Wu</b>, Li Zhao, Tao Qin, Xueqi Cheng and Tie-Yan Liu
conference: In 16th Annual Conference of the North American Chapter of the Association for Computational Linguistics - Human Language Technologies <b>(NAACL-2018) </b>
venue: ''
paperurl: 'https://www.aclweb.org/anthology/N18-1073.pdf'
citation: '<br>
@inproceedings{gao2018efficient,<br>
  title={Efficient sequence learning with group recurrent networks},<br>
  author={Gao, Fei and Wu, Lijun and Zhao, Li and Qin, Tao and Cheng, Xueqi and Liu, Tie-Yan},<br>
  booktitle={Proceedings of the 2018 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, <br> Volume 1 (Long Papers)},<br>
  pages={799--808},<br>
  year={2018}<br>
}'

---
<h2><strong>Abstract</strong></h2>
Recurrent neural networks  have achieved state-of-the-art  results  in  many  artificial  intelligence  tasks,  such  as language  modeling, neural machine translation, speech recognition and  so on.  One  of  the  key  factors  to  the sesuccesses is big  models.  However,  training such  big  models  usually  takes  days  or  even weeks  of  time  even  if  using  tens  of  GPU cards.   In this paper,  we propose an efficient architecture to improve the efficiency of such RNN model training, which adopts the group strategy for recurrent layers, while exploiting the representation rearrangement strategy between layers as well as time steps. To demonstrate the advantages of our models, we conduct experiments on several datasets and tasks. The results show that our architecture achieves comparable or better accuracy comparing with baselines, with a much smaller number of parameters and at a much lower computational cost.

\[[PDF](https://www.aclweb.org/anthology/N18-1073.pdf)\]  