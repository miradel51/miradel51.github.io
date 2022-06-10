---
title: "MGIMN: Multi-Grained Interactive Matching Network for Few-shot Text Classification"
collection: 
permalink: /publication/20220411_xfewshot_arxiv
excerpt: ''
date: 2022-04-11
author: Jianhai Zhang, <b>Mieradilijiang Maimaiti</b>, Xing Gao, Yuanhang Zheng, and Ji Zhang*
conference: In International Conference on North American Chapter of the Association for Computational Linguistics <b>(NAACL, 2022)</b> (*=corresponding author) (Long paper, poster) 
venue: 'https://arxiv.org/pdf/2204.04952.pdf'
paperurl: ''
citation: '<br>
@inproceedings{jianhai22_xfewshot,<br>
  title={MGIMN: Multi-Grained Interactive Matching Network for Few-shot Text Classification},<br>
  author={Jianhai Zhang, Mieradilijiang Maimaiti, Xing Gao, Yuanhang Zheng, and Ji Zhang},<br>
  booktitle={NAACL},<br>
  year={2022},<br>
}'


---
<h2><strong>Abstract</strong></h2>
Text classification struggles to generalize to unseen classes with very few labeled text instances per class.
In such a few-shot learning (FSL) setting, metric-based meta-learning approaches have shown promising results. 
Previous studies mainly aim to derive a prototype representation for each class.
However, they neglect that it is challenging-yet-unnecessary to construct a compact representation which expresses the entire meaning for each class.
They also ignore the importance to capture the inter-dependency between query and the support set for few-shot text classification. 
To deal with these issues, we propose a meta-learning based method \textbf{MGIMN} which performs instance-wise comparison followed by aggregation to generate class-wise matching vectors instead of prototype learning.
The key of instance-wise comparison is the interactive matching within the class-specific context and episode-specific context. 
Extensive experiments demonstrate that the proposed method significantly outperforms the existing state-of-the-art approaches, under both the standard FSL and generalized FSL settings.

\[[PDF](https://arxiv.org/pdf/2204.04952.pdf)\]\[[Poster](https://miradel51.github.io/files/naacl2022_poster.pdf)\]\[[Slides](https://miradel51.github.io/files/naacl2022_slides_3.pdf)\]\[[Video](https://miradel51.github.io/files/naacl22_video_small.mp4)\]



