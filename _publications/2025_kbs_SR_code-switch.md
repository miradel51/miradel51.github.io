---
title: "Improving Cross-lingual Representation for Semantic Retrieval with Code-switching"
collection: 
permalink: /publication/2025_kbs_SR_code-switch
excerpt: ''
date: 2025-06-03
author: <b>Mieradilijiang Maimaiti</b>*†, Yuanhang Zheng*, Ji Zhang, Yue Zhang, Wenpei Luo and Kaiyu Huang
conference: In Knowledge-Based Systems <b>(KBS, 2025)</b>  (*=equal contribution, †=corresponding author)
venue: ''
paperurl: 'https://arxiv.org/pdf/2403.01364.pdf'
citation: '<br>
@inproceedings{maimaiti2024_SR_codeswitch,<br>
  title={Improving Cross-lingual Representation for Semantic Retrieval with Code-switching},<br>
  author={Mieradilijiang Maimaiti, Yuanhang Zheng, Ji Zhang, Yue Zhang, Wenpei Luo and Kaiyu Huang},<br>
  journal={Knowledge-Based Systems (KBS)},<br>
  year={2025},<br>
}'


---
<h2><strong>Abstract</strong></h2>
Semantic Retrieval (SR) has become an indispensable part of the FAQ system in the task-oriented question-answering (QA) dialogue scenario. 
The demands for a cross-lingual smart-customer-service system for an e-commerce platform or some particular business conditions have been increasing recently. 
Most previous studies exploit cross-lingual pre-trained models (PTMs) for multilingual knowledge retrieval directly, while some others also leverage the continual pre-training before fine-tuning PTMs on the downstream tasks. 
However , no matter which schema is used, the previous work ignores to inform PTMs of some features of the downstream task, i.e. train their PTMs without providing any signals related to SR. 
To this end, in this work, we propose an Alternative Cross-lingual PTM for SR via code-switching. We are the first to utilize the code-switching approach for cross-lingual SR. 
Besides, we introduce the novel code-switched continual pre-training instead of directly using the PTMs on the SR tasks. 
The experimental results show that our proposed approach consistently outperforms the previous SOTA methods on SR and semantic textual similarity (STS) tasks 
with three business corpora and four open datasets in 20+ languages.

\[[PDF](https://www.sciencedirect.com/science/article/pii/S0950705125009645?dgcid=author)\]\[[Code](https://github.com/miradel51/codemix_ptm)\]
