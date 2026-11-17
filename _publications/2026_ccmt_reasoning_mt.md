---
title: "Are Reasoning and Refining Really Helpful for LLM-based Machine Translation in Low-Resource Scenarios?"
collection: 
permalink: /publication/2026_ccmt_reasoning_mt
excerpt: ''
date: 2026-11-13
author: Dezhi Wang, <b>Mieradilijiang Maimaiti</b>*, Yi Chen, Shibo Zhang, Zhengyi Guo, Zhexin Li, and Wushour Silamu
conference: The 22nd China Conference on Machine Translation and Multilingual Technology <b>(CCMT, 2026)</b> (*=corresponding author) <span style="color:red">Best paper</span>
venue: ''
paperurl: 'http://sc.cipsc.org.cn/mt/conference/2026/files/accepted-papers/paper-023.pdf'
citation: '<br>
@INPROCEEDINGS{wang2026,<br>
  author={Dezhi Wang, Mieradilijiang Maimaiti, Yi Chen, Shibo Zhang, Zhengyi Guo, Zhexin Li, and Wushouer Silamu},<br>
  booktitle={The 22nd China Conference on Machine Translation and Multilingual Technology (CCMT, 2026)},<br>
  title={Are Reasoning and Refining Really Helpful for LLM-based Machine Translation in Low-Resource Scenarios?},<br>
  year={2026},<br>
  volume={},<br>
  number={},<br>
  pages={},<br>
  keywords={Large Language Models; Machine Translation; Low-Resource Languages; Chain-of-Thought; Quality Estimation},<br>
  doi={},<br>
  }'

---
<h2><strong>Abstract</strong></h2>
Large language models (LLMs) perform well on high-resource languages but struggle with low-resource ones. 
Direct prompting often produces translations in a single step, without leveraging relevant linguistic information or reasoning. 
We propose KnT (Knowledge-to-Translation), a refined chain-of-thought (CoT) approach in which the model first generates translation-relevant linguistic knowledge, including a demonstration, topic information, a dictionary chain, and an explanation of a difficult word, then incorporates it into different prompts to guide translation. 
Multiple candidates are generated, with the best selected via a reference-free quality estimator. 
Experiments on FLORES-200, IWSLT, and CCMatrix, among others, show consistent improvements over strong baselines on common translation metrics such as XCOMET-XL and BLEURT-20, demonstrating that reasoning over extracted linguistic knowledge effectively improves low-resource translation. 
The code and data are publicly available. https://github.com/kyriezhizhi-ops/knt

\[[PDF](http://sc.cipsc.org.cn/mt/conference/2026/files/accepted-papers/paper-023.pdf)\] \[[Code](https://github.com/kyriezhizhi-ops/knt)\] \[[Poster](https://miradel51.github.io/files/ccmt2026_poster_wdz.pdf)\] \[[Slides](https://miradel51.github.io/files/ccmt2026_slides_wdz.pdf)\] \[[Best Paper](https://miradel51.github.io/files/ccmt2026_betpaper_wdzs.pdf)\]



