---
title: "Mixture of Spectral Experts for Audio Deepfake Detection"
collection: 
permalink: /publication/2026_interspeech_moe
excerpt: ''
date: 2026-06-04
author: Yaxuan Qiu, Zhe Li, <b>Mieradilijiang Maimaiti</b>*, Zunwang Ke, Yanbing Li, and Wushour Silamu
conference: In International Conference <b>Interspeech (2026)</b> (*=corresponding author)
venue: 'Sydney, Australia'
paperurl: 'https://www.researchgate.net/publication/407042877_Mixture_of_Spectral_Experts_for_Audio_Deepfake_Detection'
citation: '<br>
@inproceedings{qiu26_interspeech,<br>
  title     = {{Mixture of Spectral Experts for Audio Deepfake Detection}},<br>
  author    = {Yaxuan Qiu and Zhe Li and Mieradilijiang Maimaiti and Zunwang Ke and Wushour Silamu},<br>
  year      = {2026},<br>
  booktitle = {{Interspeech 2026}},<br>
  pages     = {1053--1057},<br>
  doi       = {10.21437/Interspeech.2026-661},<br>
  issn      = {2958-1796},<br>
}'

---
<h2><strong>Abstract</strong></h2>
Recent advances in neural speech synthesis have produced highly natural waveforms, making audio deepfake detection increasingly challenging as spoofing artifacts become less perceptible. 
Although pre-trained speech models provide robust representations, they may overlook low-level physical cues, particularly magnitude and phase information. 
To address this limitation, we propose a detection framework that combines a frequency audio encoder (FAE) with spectral parameter-efficient fine-tuning. 
The FAE explicitly models magnitude and phase cues, while the proposed Mixture of Spectral Experts (MoSE) efficiently adapts the pre-trained speech model to generation-dependent distribution shifts. 
By applying low-rank updates in the singular value decomposition (SVD) domain while keeping the singular bases frozen, MoSE facilitates task-specific adaptation to spoofing-related spectral artifacts. 
Evaluations on ASVspoof 2019 LA, ASVspoof 2021 LA/DF, and In-the-Wild benchmarks demonstrate the effectiveness of our approach and its strong generalization to unseen channel variations and real-world spoofing attacks.

\[[PDF](https://www.isca-archive.org/interspeech_2026/qiu26_interspeech.html)\]
