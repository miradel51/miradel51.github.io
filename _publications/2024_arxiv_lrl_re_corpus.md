---
title: "How Good are LLMs at Relation Extraction under Low-Resource Scenario? Comprehensive Evaluation"
collection: 
permalink: /publication/2024_arxiv_lrl_re_corpus
excerpt: ''
date: 2024-02-16
author: Dawulie Jinensibieke*, <b>Mieradilijiang Maimaiti</b>†, Wentao Xiao*, Yuanhang Zheng, and Xiaobo Wang†
conference: In Arxiv <b>(2024)</b> (*=equal contribution, †=corresponding author)
venue: ''
paperurl: 'https://arxiv.org/abs/2406.11162'
citation: '<br>
@inproceedings{dawulie2024_lrls_re,<br>
  title={How Good are LLMs at Relation Extraction under Low-Resource Scenario? Comprehensive Evaluation},<br>
  author={Dawulie Jinensibieke, Mieradilijiang Maimaiti, Wentao Xiao, Yuanhang Zheng, Xiaobo Wang},<br>
  booktitle={Arxiv},<br>
  year={2024},<br>
}'


---
<h2><strong>Abstract</strong></h2>
Relation Extraction (RE) serves as a crucial technology for transforming unstructured text into structured information, especially within the framework of Knowledge Graph development. 
Its importance is emphasized by its essential role in various downstream tasks. 
Besides the conventional RE methods which are based on neural networks and pre-trained language models, large language models (LLMs) are also utilized in the research field of RE. 
However, on low-resource languages (LRLs), both conventional RE methods and LLM-based methods perform poorly on RE due to the data scarcity issues. 
To this end, this paper constructs low-resource relation extraction datasets in 10 LRLs in three regions (Central Asia, Southeast Asia and Middle East). 
The corpora are constructed by translating the original publicly available English RE datasets (NYT10, FewRel and CrossRE) using an effective multilingual machine translation. 
Then, we use the language perplexity (PPL) to filter out the low-quality data from the translated datasets. 
Finally, we conduct an empirical study and validate the performance of several open-source LLMs on these generated LRL RE datasets.

\[[PDF](https://arxiv.org/abs/2406.11162)\] \[[Code](https://github.com/victor812-hub/entity_datasets)\] \[[Corpus](https://huggingface.co/datasets/Wentaolazy/entity_dataset)\]
