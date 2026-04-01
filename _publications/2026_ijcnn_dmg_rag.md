---
title: "DMG-RAG: Dynamic Multi-Grained Retrieval Augmented Generation for Multi-Hop QA"
collection: 
permalink: /publication/2026_ijcnn_dmg_rag
excerpt: ''
date: 2026-03-20
author: Yu Pei, <b>Mieradilijiang Maimaiti</b>*, Yi Chen, Wu Le, Zhuofei Xie,  and Jiawei Chen
conference: In International Joint Conference on Neural Networks <b>(IJCNN, 2026)</b> (*=corresponding author) (Main track, Long paper)
venue: ''
paperurl: 'https://www.researchgate.net/publication/403332946_DMG-RAG_Dynamic_Multi-Grained_Retrieval_Augmented_Generation_for_Multi-Hop_QA'
citation: '<br>
@inproceedings{shibo2026_llm_mt_rag_agent,<br>
  title={DMG-RAG: Dynamic Multi-Grained Retrieval Augmented Generation for Multi-Hop QA},<br>
  author={Yu Pei, Mieradilijiang Maimaiti, Yi Chen, Wu Le, Zhuofei Xie,  and Jiawei Chen},<br>
  journal={International Joint Conference on Neural Networks (IJCNN)},<br>
  year={2026},<br>
}'

---
<h2><strong>Abstract</strong></h2>
Retrieval-Augmented Generation (RAG) enhances multi-hop question answering by grounding large language models (LLMs) in retrieved evidence, yet its effectiveness is highly sensitive to chunk granularity and context construction under a fixed token budget. 
Sentence-level chunks can be precise but often fragment evidence chains, while paragraph- and document-level chunks provide broader coverage at the risk of introducing redundancy and irrelevant content. 
We propose \textbf{DMG-RAG}, a query-aware multi-grained RAG framework that coordinates chunking, retrieval, and budgeted context construction with two lightweight modules. 
We build aligned indices on the same corpus at three simple granularities (sentence, paragraph, and document). A query-conditioned \emph{Router} dynamically allocates stage-1 retrieval quota set across granularities to shape an adaptive candidate pool for each query. 
Given the candidate pool, a \emph{Budgeter} performs budget-constrained evidence selection by jointly considering relevance, chunk length, and redundancy, and assembles a compact evidence set via a deterministic greedy packing procedure guided by a learned scoring function. 
Experiments on HotpotQA, 2WikiMultiHopQA, and MuSiQue demonstrate that DMG-RAG consistently outperforms strong baselines under EM and F1, yielding substantial average gains (up to 7--8 points). The code is publicly available
The code is publicly available at \[[GitHub](https://github.com/zza-zaa/DMG-RAG)\].

\[[PDF](https://www.researchgate.net/publication/403332946_DMG-RAG_Dynamic_Multi-Grained_Retrieval_Augmented_Generation_for_Multi-Hop_QA)\]



