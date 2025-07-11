---
title: "Enriching the Transfer Learning with Pre-trained Lexicon Embedding for Low-Resource Neural Machine Translation"
collection: publications
permalink: /publication/2022_tst_tl_share
excerpt: ''
date: 2022-02-25
author: <b>Mieradilijiang Maimaiti</b>, Yang Liu*, Huanbo Luan, and Maosong Sun
conference: In TSINGHUA SCIENCE AND TECHNOLOGY <b>(TST, 2022)</b> (*=corresponding author)
venue: ''
paperurl: 'https://ieeexplore.ieee.org/xpl/mostRecentIssue.jsp?punumber=5971803'
citation: '<br>
@article{Maimaiti2020EnrichingTT,<br>
  title={Enriching the Transfer Learning with Pre-Trained Lexicon Embedding for Low-Resource Neural Machine Translation},<br>
  author={M. Maimaiti and Y. Liu and Huanbo Luan and M. Sun},<br>
  journal={Tsinghua Science \& Technology (TST)},<br>
  year={2022},<br>
  volume={27},<br>
  issue={1},<br>
  pages={150 - 163},<br>
}'

---
<h2><strong>Abstract</strong></h2>
Most state-of-the-art (SOTA) neural machine translation (NMT) systems today achieve outstanding results based only on large parallel corpora. However, the translation quality of NMT for morphologically rich languages (MRLs) is still unsatisfactory, mainly because of the data sparsity problem encountered in low-resource languages (LRLs). The large-scale parallel corpora for high-resource languages (HRLs) are easily obtainable. In the low-resource NMT paradigm, transfer learning (TL) has been developed into one of the most efficient methods. Obviously, it is difficult to train the model on HRLs to include both the information of parent and child models.
In this work, we aim to address this issue by proposing the mixed transfer learning (MTL) method for LRLs via shared vocabulary between parent and child languages without leveraging back translation or manually injecting noises. First, we trained the HRLs as the parent model with its vocabularies. Then, we combined the parent and child language pairs using the oversampling method to trained the mixed model initialized by the previous parent model. Finally, we fine-tuned the morphologically rich child model using a mixed model. Besides, we explored some exciting discoveries on the original TL approach. Experimental results showed that our model consistently outperforms four SOTA methods on two MRLs - Azerbaijani (Az) and Uzbek (Uz). Meanwhile, our approach is practical and significantly better, achieving improvements of up to 4.94 and 4.84 BLEU points for the  two 
child languages Az - Ch and Uz - Ch, respectively.

\[[PDF](https://ieeexplore.ieee.org/document/9515788)\]  
