---
title: "Vision-to-Text: Benchmarking Multimodal LLMs on Extremely Low-Resource Languages"
collection: 
permalink: /publication/2026_ijcnn_mllm_mt_bench_lrls
excerpt: ''
date: 2026-03-20
author: Shuoshuo Hou, <b>Mieradilijiang Maimaiti</b>*, Zhexin Li, Jiaxin Wang, Ahmad Hassan, Kaishaer Jiapaer, Nilufar Abdurakhmonova, Urinbayeva Roza, Madina Mansurova, Shormakova Assem, Gulnar Murat, Wu Le, and Wushour Silamu
conference: In International Joint Conference on Neural Networks <b>(IJCNN, 2026)</b> (*=corresponding author) (Main track, Long paper)
venue: ''
paperurl: 'https://www.researchgate.net/publication/403332870_Vision-to-Text_Benchmarking_Multimodal_LLMs_on_Extremely_Low-Resource_Languages'
citation: '<br>
@inproceedings{shuoshuo2026_mllm_mt_benchmark_lrl,<br>
  title={Vision-to-Text: Benchmarking Multimodal LLMs on Extremely Low-Resource Languages},<br>
  author={Shuoshuo Hou, Mieradilijiang Maimaiti, Zhexin Li, Jiaxin Wang, Ahmad Hassan, Kaishaer Jiapaer, Nilufar Abdurakhmonova, Urinbayeva Roza, Madina Mansurova, Shormakova Assem, Gulnar Murat, Wu Le, and Wushour Silamu},<br>
  journal={International Joint Conference on Neural Networks (IJCNN)},<br>
  year={2026},<br>
}'

---
<h2><strong>Abstract</strong></h2>
Multimodal large language models (MLLMs) have emerged as a dominant paradigm for visually grounded language tasks. 
However, multimodal machine translation (MMT) remains constrained by the scarcity of multimodal data for low-resource languages (LRLs). 
Previously proposed approaches have also explored some strategies for machine translation with MLLMs under low-resource scenarios; 
however, they still face the critical bottleneck of a lack of high-quality multimodal datasets for extremely low-resource languages. 
To this end, we propose a novel and straightforward method for constructing a high-quality benchmark for MMT in extremely low-resource languages by harnessing LLMs and leveraging a human evaluation strategy. 
The presented approach for building the multimodal low-resource benchmark consists of three phases. 
First, we select an optimal visual captioner via metric-driven evaluation to ensure reliable grounding; 
Second, we use a hybrid ensemble of diverse translation models to reduce bias and improve the fluency -faithfulness balance; 
Finally, we apply a triangular quality estimation scheme-reference-free quality, semantic consistency, and visual alignment-to filter candidates. 
We conduct extensive experiments on multiple corpora using various evaluation metrics. 
The results show that strong baselines (e.g., Qwen3-VL-8B and LLaVA-v1.6-7B), when fine-tuned on our proposed benchmark, achieve substantial improvements not only on our benchmark but also on well-known multimodal datasets 
such as Visual Genome and Multi30K, with average gains of +7.67, +8.50, and +9.67 on COMET-Kiwi, CLIP, and BERTScore, respectively. The corresponding code and constructed high-quality multimodal low-resource languages benchmark are publicly available 
The code is publicly available at \[[Huggingface](https://huggingface.co/datasets/yumoya/SilkRoad-VL)\].

\[[PDF](https://www.researchgate.net/publication/403332870_Vision-to-Text_Benchmarking_Multimodal_LLMs_on_Extremely_Low-Resource_Languages)\]
