---
title: "Visual-Semantic Dual-Decoder Collaboration for Scene Text Recognition"
collection: 
permalink: /publication/2025_prcv_visual_sem
excerpt: ''
date: 2025-08-23
author: Chuanlong Liu, Shuangying li, Miaomiao Xu*, <b>Mieradilijiang Maimaiti</b>, and Wushour Silamu*
conference: In Chinese Conference on Pattern Recognition and Computer Vision <b>(PRCV, 2025)</b> (*=corresponding author) (Long paper, poster)
venue: ''
paperurl: 'https://www.researchgate.net/publication/395099232_Visual-Semantic_Dual-Decoder_Collaboration_for_Scene_Text_Recognition'
citation: '<br>
@inproceedings{liu25_visual_sem,<br>
  title={Visual-Semantic Dual-Decoder Collaboration for Scene Text Recognition},<br>
  author={Chuanlong Liu, Shuangying li, Miaomiao Xu, Mieradilijiang Maimaiti, and Wushour Silamu},<br>
  journal={Conference: Chinese Conference on Pattern Recognition and Computer Vision (PRCV)},<br>
  year={2025},<br>
}'


---
<h2><strong>Abstract</strong></h2>
Scene text recognition aims to extract textual content from natural images with text in various languages and under diverse visual conditions. 
While recent Transformer-based methods have achieved impressive results, they primarily target English and other resource-rich languages. 
Prior work has leveraged language modeling and robust architectures to improve recognition under challenging conditions. 
However, these methods often rely on large-scale annotated datasets and struggle with low-resource, morphologically complex scripts like Uyghur, which present challenges such as allographic synonymy, connected writing, and limited training data. 
To address these issues, we propose a dual-decoder framework for Uyghur scene text recognition, 
comprising a shared visual encoder and two complementary decoders: a Permutation Language Modeling Decoder for semantic modeling and a Concatenation-Coupling Decoder for enhanced visual-semantic interaction. 
We further introduce a lightweight fusion module guided by KL divergence loss and adopt a progressive training strategy to enhance convergence. 
Our method achieves 95.93% accuracy on a self-built Uyghur dataset, surpassing DAN and CDistNet by 0.54% and 2.97%, respectively, demonstrating its effectiveness on low-resource and morphologically complex scripts. 
It also yields a 0.38% average gain across seven English benchmarks, highlighting strong cross-lingual generalizability.

\[[PDF](https://www.researchgate.net/publication/395099232_Visual-Semantic_Dual-Decoder_Collaboration_for_Scene_Text_Recognition)\]



