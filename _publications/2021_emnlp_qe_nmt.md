---
title: "Self-Supervised Quality Estimation for Machine Translation"
collection: publications
permalink: /publication/2021_emnlp_qe_nmt
excerpt: ''
date: 2021-08-26
author: Yuanhang Zheng, Zhixing Tan, Meng Zhang, <b>Mieradilijiang Maimaiti</b>, Huanbo Luan, Maosong Sun, Qun Liu and Yang Liu
conference: In International Conference on Empirical Methods in Natural Language Processing <b>(EMNLP, 2021)</b> (Long paper, poster)
venue: ''
paperurl: 'https://2021.emnlp.org/'
citation: '<br>
@article{Zheng:2021:EMNLP,<br>
  title={Self-Supervised Quality Estimation for Machine Translation},<br>
  author={Zheng, Yuanhang and Tan, Zhixing and Zhang, Meng and Maimaiti, Mieradilijiang and Luan, Huanbo and Sun, Maosong and Liu, Qun and Liu, Yang},<br>
  journal={International Conference on Empirical Methods in Natural Language Processing (EMNLP)},<br>
  year={2021},<br>
}'

---
<h2><strong>Abstract</strong></h2>
Quality estimation (QE) of machine translation (MT) aims to evaluate the quality of machine-translated sentences without references, and is important in practical applications of MT. Training QE models requires massive parallel data with hand-crafted quality annotations, which are time-consuming and labor-intensive to obtain. To address the issue of the absence of annotated training data, previous studies attempt to develop unsupervised QE methods. However, very few of them can be applied to both sentence- and word-level tasks, and they may suffer from the noise in the synthetic data. 
To reduce the negative im015 pact of the noise, we propose a self-supervised method for both sentence- and word-level QE, which performs quality estimation by recovering the masked target words. Experimental results show that our method outperforms previous unsupervised methods on several QE tasks in different language pairs and domains.

\[[PDF](https://miradel51.github.io/files/emnlp2021_qe.pdf)\]\[[Code](https://github.com/THUNLP-MT/SelfSupervisedQE)\]\[[Blog](https://thumtblog.github.io/2021/09/20/self-supervised-qe/)\]\[[Poster](https://miradel51.github.io/files/emnlp2021_yuanhang_poster.pdf)\]\[[Slides](https://miradel51.github.io/files/emnlp2021_yuanhang_slides.pdf)\]\[[Video](https://miradel51.github.io/files/emnlp2021_yuanhang_video.pdf)\]
