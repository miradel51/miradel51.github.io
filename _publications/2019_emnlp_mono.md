---
title: "Exploiting Monolingual Data at Scale for Neural Machine Translation"
collection: publications
permalink: /publication/2019_emnlp_mono
excerpt: ''
date: 2019-11-03
author: <b>Lijun Wu</b>*, Yiren Wang*, Yingce Xia, Tao Qin, Jianhuang Lai, and Tie-Yan Liu
conference: In 2019 Conference on Empirical Methods in Natural Language Processing <b>(EMNLP-2019)</b> (*=equal contribution)
venue: ''
paperurl: 'https://www.aclweb.org/anthology/D19-1430.pdf'
citation: '<br>
@inproceedings{wu2019exploiting,<br>
  title={Exploiting monolingual data at scale for neural machine translation},<br>
  author={Wu, Lijun and Wang, Yiren and Xia, Yingce and Tao, QIN and Lai, Jianhuang and Liu, Tie-Yan},<br>
  booktitle={Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP)},<br>
  pages={4198--4207},<br>
  year={2019}<br>
}'

---
<h2><strong>Abstract</strong></h2>
While target-side monolingual data has been proven to be very useful to improve neural machine translation (briefly, NMT) through back translation, source-side monolingual data is not well investigated. In this work, we study how to use both the source-side and target-side monolingual data for NMT, and propose an effective strategy leveraging both of them. First, we generate synthetic bitext by translating monolingual data from the two domains into the other domain using the models pretrained on genuine bitext. Next, a model is trained on a noised version of the concatenated synthetic bitext where each source sequence is randomly corrupted. Finally, the model is fine-tuned on the genuine bitext and a clean version of a subset of the synthetic bitext without adding any noise. Our approach achieves state-of-the-art results on WMT16, WMT17, WMT18 English↔German translations and WMT19 German→French translations, which demonstrate the effectiveness of our method. We also conduct a comprehensive study on how each part in the pipeline works.

\[[PDF](https://www.aclweb.org/anthology/D19-1430.pdf)\]  