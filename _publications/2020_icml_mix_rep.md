---
title: "Temporally Correlated Task Scheduling for Sequence Learning"
collection: publications
permalink: /publication/2021_icml_temp_cor
excerpt: ''
date: 2021-05-08
author: Xueqing Wu, Lewen Wang, Yingce Xia, Weiqing Liu, <b>Lijun Wu</b>, Shufang Xie, Tao Qin, and Tie-Yan Liu
conference: In Thirty-eighth International Conference on Machine Learning <b>(ICML-2021)</b>
venue: ''
paperurl: ''
citation: '<br>
@inproceedings{wu2021temp,<br>
  title={Temporally Correlated Task Scheduling for Sequence Learning},<br>
  author={Xueqing Wu, Lewen Wang, Yingce Xia, Weiqing Liu, Lijun Wu, Shufang Xie, Tao Qin, and Tie-Yan Liu},<br>
  booktitle={International Conference on Machine Learning},<br>
  year={2021}<br>
}'

---
<h2><strong>Abstract</strong></h2>
Sequence learning has attracted much research attention from the machine learning community in recent years. In many applications, a sequence learning task is usually associated with multiple temporally correlated auxiliary tasks, which are different in terms of how much input information to use or which future step to predict. For example, (i) in simultaneous machine translation, one can conduct translation under different latency (i.e., how many input words to read/wait before translation); (ii) in stock trend forecasting, one can predict the price of a stock in different future days (e.g., tomorrow, the day after tomorrow). While it is clear that those temporally correlated tasks can help each other, there is a very limited exploration on how to better leverage multiple auxiliary tasks to boost the performance of the main task. In this work, we introduce a learnable scheduler to sequence learning, which can adaptively select auxiliary tasks for training depending on the model status and the current training data. The scheduler and the model for the main task are jointly trained through bi-level optimization. Experiments show that our method significantly improves the performance of simultaneous machine translation and stock trend forecasting. We will release our code at Github after the anonymous period.

\[[PDF]()\] 