---
title: "Sequence Prediction with Unlabeled Data by Reward Function Learning"
collection: publications
permalink: /publication/2017_ijcai_sequence
excerpt: ''
date: 2017-08-19
author: <b>Lijun Wu</b>, Li Zhao, Tao Qin, Jianhuang Lai and Tie-Yan Liu
conference: In 26th International Joint Conference on Artifcial Intelligence <b>(IJCAI-2017)</b>
venue: ''
paperurl: 'https://www.ijcai.org/proceedings/2017/0432.pdf'
citation: '<br>
@inproceedings{wu2017sequence, <br>
  title={Sequence Prediction with Unlabeled Data by Reward Function Learning.},<br>
  author={Wu, Lijun and Zhao, Li and Qin, Tao and Lai, Jianhuang and Liu, Tie-Yan},<br>
  booktitle={IJCAI},<br>
  pages={3098--3104},<br>
  year={2017} <br>
}'

---
<h2><strong>Abstract</strong></h2>
Reinforcement learning (RL), which has been successfully  applied  to  sequence  prediction, introduces rewardas sequence-level supervision signal to evaluate  the quality of a generated sequence. Existing RL approaches use the  ground-truth  sequence to define reward, which limits the application of RL techniques to labeled data. Since labeled data is usually scarce and/or costly to collect, it is desirable to leverage large-scale unlabeled data. In this paper, we extend existing RL methods for sequence  prediction to exploit unlabeled  data.  We propose to learn the reward function from labeled data and use the predicted reward as pseudo reward for unlabeled data so that we can learn from unlabeled data using the pseudo reward. To get good pseudo  reward  on  unlabeled data,  we  propose  a RNN-based  reward  network  with  attention  mechanism, trained with purposely biased data distribution. Experiments show that the pseudo reward canprovide  good supervision and guide the learning process on unlabeled data. We observe significant improvements on both neural machine translation and text summarization.

\[[PDF](https://www.ijcai.org/proceedings/2017/0432.pdf)\]  