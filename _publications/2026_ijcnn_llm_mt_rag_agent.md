---
title: "Retrieve, Refine, and Translate: LLM-Based Translation for Low-Resource Languages"
collection: 
permalink: /publication/2026_ijcnn_llm_mt_rag_agent
excerpt: ''
date: 2026-03-20
author: Shibo Zhang, <b>Mieradilijiang Maimaiti</b>*, Zhengyi Guo, Dezhi Wang, Wu Le, Zhuofei Xie, Jiawei Chen, and Wushour Silamu
conference: In International Joint Conference on Neural Networks <b>(IJCNN, 2026)</b> (*=corresponding author) (Main track, Long paper)
venue: ''
paperurl: 'https://www.researchgate.net/publication/403332692_Retrieve_Refine_and_Translate_LLM-Based_Translation_for_Low-Resource_Languages'
citation: '<br>
@inproceedings{shibo2026_llm_mt_rag_agent,<br>
  title={Retrieve, Refine, and Translate: LLM-Based Translation for Low-Resource Languages},<br>
  author={Shibo Zhang, Mieradilijiang Maimaiti, Zhengyi Guo, Dezhi Wang, Wu Le, Zhuofei Xie, Jiawei Chen, and Wushour Silamu},<br>
  journal={International Joint Conference on Neural Networks (IJCNN)},<br>
  year={2026},<br>
}'

---
<h2><strong>Abstract</strong></h2>
Large language models (LLMs) have demonstrated promising performance in machine translation, and retrieval-augmented generation (RAG) can further improve translation quality by incorporating external examples and leveraging the in-context learning capabilities of LLMs. 
However, in low-resource scenarios, empirical studies indicate that generated translations still exhibit diverse and persistent errors, and effectively refining 
such errors remains a challenge. In this work, we present a two-stage refinement framework for low-resource machine translation. 
The first stage focuses on correcting major translation errors through implicit refinement that exploits retrieved parallel examples, together with auxiliary knowledge guidance. 
The second stage introduces quality-oriented feedback to identify and revise the remaining errors iteratively. 
By integrating implicit correction with explicit feedback, the proposed framework provides a structured refinement process to improve translation quality. 
Extensive experiments on three benchmarks (FLORES-200, NTREX-128, and TICO-19) covering 8 low-resource languages demonstrate the effectiveness of our framework, showing that our introduced approach achieves highly competitive performance against strong baseline systems with XCOMET and BLEURT. 
The code is publicly available at \[[GitHub](https://github.com/qaza200/2stagerefine)\].

\[[PDF](https://www.researchgate.net/publication/403332692_Retrieve_Refine_and_Translate_LLM-Based_Translation_for_Low-Resource_Languages)\]



