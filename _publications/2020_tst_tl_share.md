---
title: "Enriching the Transfer Learning with Pre-trained Lexicon Embedding for Low-Resource Neural Machine Translation"
collection: publications
permalink: /publication/2020_tst_tl_share
excerpt: ''
date: 2020-09-25
author: <b>Mieradilijiang Maimaiti</b>, Yang Liu*, Huanbo Luan, and Maosong Sun
conference: In TSINGHUA SCIENCE AND TECHNOLOGY (TST) <b>(TST, 2020)</b> (*=corresponding author)
venue: ''
paperurl: ''
citation: ''

---
<h2><strong>Abstract</strong></h2>
Most state-of-the-art (SOTA) neural machine translation (NMT) systems today achieve outstanding results based only on large parallel corpora. However, the translation quality of NMT for morphologically rich languages (MRLs) is still unsatisfactory, mainly because of the data sparsity problem encountered in low-resource languages (LRLs). The large-scale parallel corpora for high-resource languages (HRLs) are easily obtainable. In the low-resource NMT paradigm, transfer learning (TL) has been developed into one of the most efficient methods. Obviously, it is difficult to train the model on HRLs to include both the information of parent and child models.
In this work, we aim to address this issue by proposing the mixed transfer learning (MTL) method for LRLs via shared vocabulary between parent and child languages without leveraging back translation or manually injecting noises. First, we trained the HRLs as the parent model with its vocabularies. Then, we combined the parent and child language pairs using the oversampling method to trained the mixed model initialized by the previous parent model. Finally, we fine-tuned the morphologically rich child model using a mixed model. Besides, we explored some exciting discoveries on the original TL approach. Experimental results showed that our model consistently outperforms four SOTA methods on two MRLs - Azerbaijani (Az) and Uzbek (Uz). Meanwhile, our approach is practical and significantly better, achieving improvements of up to 4.94 and 4.84 BLEU points for the  two 
child languages Az - Ch and Uz - Ch, respectively.

\[[PDF](https://miradel51.github.io/files/tst_2020_tl_share.pdf)\]  
