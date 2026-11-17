---
title: "T$D^2$：Text-Driven Decoding for Mitigating Image-Induced Hallucination in Low-Resource Multimodal Translation"
collection: 
permalink: /publication/2026_ccmt_hallucinations_mllm_mt
excerpt: ''
date: 2026-11-13
author: Yi Chen, <b>Mieradilijiang Maimaiti</b>*, Yu Pei, Jiaxin Wang, Shuoshuo Hou, Zhexin Li, Zhengyi Guo, and Wushour Silamu
conference: The 22nd China Conference on Machine Translation and Multilingual Technology <b>(CCMT, 2026)</b> (*=corresponding author) (<b>Best poster paper</b>)
venue: ''
paperurl: 'http://sc.cipsc.org.cn/mt/conference/2026/files/accepted-papers/paper-071.pdf'
citation: '<br>
@INPROCEEDINGS{yichen2026,<br>
  author={Yi Chen, Mieradilijiang Maimaiti, Yu Pei, Jiaxin Wang, Shuoshuo Hou, Zhexin Li, Zhengyi Guo, and Wushour Silamu},<br>
  booktitle={The 22nd China Conference on Machine Translation and Multilingual Technology (CCMT, 2026)},<br>
  title={T$D^2$：Text-Driven Decoding for Mitigating Image-Induced Hallucination in Low-Resource Multimodal Translation},<br>
  year={2026},<br>
  volume={},<br>
  number={},<br>
  pages={},<br>
  keywords={Multimodal Machine Translation, Low-Resource Machine Translation, Vision-Language Models, Hallucination},<br>
  doi={},<br>
  }'

---
<h2><strong>Abstract</strong></h2>
Large Vision-Language Models (LVLMs) have shown strong potential for multimodal machine translation by leveraging visual context. 
However, visual inputs can also introduce image-induced priors, leading to visually plausible but textually unfaithful translations, especially for low-resource target languages. 
We propose Text-Driven Decoding (T$D^2$), a simple, training-free method that calibrates next-token logits by contrasting those obtained from the full multimodal input with their image-only counterparts. 
By suppressing source-agnostic image-prior logits while preserving the full source-image context, T$D^2$ improves source-faithful translation without model retraining. 
Experiments on VG and Multi30K with five LVLM backbones spanning three model families show improvements over direct decoding, while comparisons on two non-Qwen backbones further demonstrate gains over VCD and ICD. 
Entity-level analyses further indicate reduced source-unsupported hallucinations in multiple settings.
The corresponding source code is available at \footnote{\url{https://github.com/chenyi240226-oss/Text-Driven-Decoding}}.

\[[PDF](http://sc.cipsc.org.cn/mt/conference/2026/files/accepted-papers/paper-071.pdf)\] \[[Code](https://github.com/chenyi240226-oss/Text-Driven-Decoding)\] \[[Poster](https://miradel51.github.io/files/ccmt2026_poster_cy.pdf)\] \[[Slides](https://miradel51.github.io/files/ccmt2026_slides_cy.pdf)\] \[[Best Poster Paper](https://miradel51.github.io/files/ccmt2026_bestposter_cy.pdf)\]



