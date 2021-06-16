---
title: "A Study of Reinforcement Learning for Neural Machine Translation"
collection: publications
permalink: /publication/2018_emnlp_rl_study
excerpt: ''
date: 2018-10-31
author: <b>Lijun Wu</b>, Fei Tian, Tao Qin, Jianhuang Lai and Tie-Yan Liu
conference: In 2018 Conference on Empirical Methods in Natural Language Processing <b>(EMNLP-2018)</b> 
venue: ''
paperurl: 'https://www.aclweb.org/anthology/D18-1397.pdf'
citation: '<br>
@inproceedings{wu2018study,<br>
  title={A Study of Reinforcement Learning for Neural Machine Translation},<br>
  author={Wu, Lijun and Tian, Fei and Qin, Tao and Lai, Jianhuang and Liu, Tie-Yan},<br>
  booktitle={Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing},<br>
  pages={3612--3621},<br>
  year={2018}<br>
}'

---
<h2><strong>Abstract</strong></h2>
Recent studies have shown that reinforcement learning (RL) is an effective approach for improving the performance of neural machine translation (NMT) system. However, due to its instability, successfully RL training is challenging, especially in real-world systems where deep models and large datasets are leveraged. In this paper, taking several large-scale translation tasks as testbeds, we conduct a systematic study on how to train better NMT models using reinforcement learning. We provide a comprehensive comparison of several important factors (e.g., baseline reward, reward shaping) in RL training. Furthermore, to fill in the gap that it remains unclear whether RL is still beneficial when monolingual data is used, we propose a new method to leverage RL to further boost the performance of NMT systems trained with source/target monolingual data. By integrating all our findings, we obtain competitive results on WMT14 English-German, WMT17 English-Chinese, and WMT17 Chinese-English translation tasks, especially setting a state-of-the-art performance on WMT17 Chinese-English translation task.

\[[PDF](https://www.aclweb.org/anthology/D18-1397.pdf)\]  \[[CODE](https://github.com/apeterswu/RL4NMT)\]