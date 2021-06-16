---
title: "Word Attention for Sequence to Sequence Text Understanding"
collection: publications
permalink: /publication/2018_aaai_word_attn
excerpt: ''
date: 2018-02-09
author: <b>Lijun Wu</b>, Fei Tian, Li Zhao, Jianhuang Lai and Tie-Yan Liu
conference: In Thirty-Second AAAI Conference on Artificial Intelligence <b>(AAAI-2018)</b>
venue: ''
paperurl: 'https://www.microsoft.com/en-us/research/wp-content/uploads/2017/11/word_attention_camera_ready.pdf'
citation: '<br>
@inproceedings{wu2018word,<br>
  title={Word attention for sequence to sequence text understanding},<br>
  author={Wu, Lijun and Tian, Fei and Zhao, Li and Lai, Jianhuang and Liu, Tie-Yan},<br>
  booktitle={Thirty-Second AAAI Conference on Artificial Intelligence},<br>
  year={2018}<br>
}'

---
<h2><strong>Abstract</strong></h2>
Attention mechanism has been a key component in Recurrent Neural Networks (RNNs) based sequence to sequence learning framework, which has been adopted in many text understanding tasks, such as neural machine translation and abstractive summarization. In these tasks, the attention mechanism models how important each part of the source sentence is to generate a target side word. To compute such importance scores, the attention mechanism summarizes the source side information in the encoder RNN hidden states (i.e., h_t), and then builds a context vector for a target side word upon a subsequence representation of the source sentence, since h_t actually summarizes the information of the subsequence containing the first t-th words in the source sentence. We in this paper, show that an additional attention mechanism called word attention, that builds itself upon word level representations, significantly enhances the performance of sequence to sequence learning. Our word attention can enrich the source side contextual representation by directly promoting the clean word level information in each step. Furthermore, we propose to use contextual gates to dynamically combine the subsequence level and word level contextual information. Experimental results on abstractive summarization and neural machine translation show that word attention significantly improve over strong baselines.

\[[PDF](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/11/word_attention_camera_ready.pdf)\]  \[[CODE](https://github.com/apeterswu/DL4NMT_Theano_wordAtt)\]  