---
title: "Machine Translation with Weakly Paired Documents"
collection: publications
permalink: /publication/2019_emnlp_wiki
excerpt: ''
date: 2019-11-03
author: <b>Lijun Wu</b>, Jinhua Zhu, Fei Gao, Di He, Tao Qin, Jianhuang Lai, and Tie-Yan Liu
conference: In 2019 Conference on Empirical Methods in Natural Language Processing <b>(EMNLP-2019)</b>
venue: ''
paperurl: 'https://www.aclweb.org/anthology/D19-1446.pdf'
citation: '<br>
@inproceedings{wu2019machine,<br>
  title={Machine Translation With Weakly Paired Documents},<br>
  author={Wu, Lijun and Zhu, Jinhua and He, Di and Gao, Fei and Tao, QIN and Lai, Jianhuang and Liu, Tie-Yan},<br>
  booktitle={Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP)},<br>
  pages={4366--4375},<br>
  year={2019} <br>
}'

---
<h2><strong>Abstract</strong></h2>
Neural machine translation, which achieves near human-level performance in some languages, strongly relies on the large amounts of parallel sentences, which hinders its applicability to low-resource language pairs. Recent works explore the possibility of unsupervised machine translation with monolingual data only, leading to much lower accuracy compared with the supervised one. Observing that weakly paired bilingual documents are much easier to collect than bilingual sentences, e.g., from Wikipedia, news websites or books, in this paper, we investigate training translation models with weakly paired bilingual documents. Our approach contains two components. 1) We provide a simple approach to mine implicitly bilingual sentence pairs from document pairs which can then be used as supervised training signals. 2) We leverage the topic consistency of two weakly paired documents and learn the sentence translation model by constraining the word distribution-level alignments. We evaluate our method on weakly paired documents from Wikipedia on six tasks, the widely used WMT16 German↔English, WMT13 Spanish↔English and WMT16 Romanian↔English translation tasks. We obtain 24.1/30.3, 28.1/27.6 and 30.1/27.6 BLEU points separately, outperforming previous results by more than 5 BLEU points in each direction and reducing the gap between unsupervised translation and supervised translation up to 50%.

\[[PDF](https://www.aclweb.org/anthology/D19-1446.pdf)\]  