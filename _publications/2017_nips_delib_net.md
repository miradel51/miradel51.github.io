---
title: "Deliberation Networks: Sequence Generation Beyond One-Pass Decoding"
collection: publications
permalink: /publication/2017_nips_delib_net
excerpt: ''
date: 2017-12-04
author: Yingce Xia, Fei Tian, <b>Lijun Wu</b>, Jianxin Lin, Tao Qin, Nenghai Yu and Tie-Yan Liu
conference: In 31st Conference on Neural Information Processing Systems <b>(NIPS-2017)</b>
venue: ''
paperurl: 'https://papers.nips.cc/paper/6775-deliberation-networks-sequence-generation-beyond-one-pass-decoding.pdf'
citation: '<br>
@inproceedings{xia2017deliberation,<br>
  title={Deliberation networks: Sequence generation beyond one-pass decoding},<br>
  author={Xia, Yingce and Tian, Fei and Wu, Lijun and Lin, Jianxin and Qin, Tao and Yu, Nenghai and Liu, Tie-Yan},<br>
  booktitle={Advances in Neural Information Processing Systems},<br>
  pages={1784--1794}, <br>
  year={2017} <br>
}'

---
<h2><strong>Abstract</strong></h2>
The encoder-decoder framework has achieved promising progress for many sequence generation tasks, including machine translation, text summarization, dialog system, image captioning, etc. Such a framework adopts an one-pass forward process while decoding and generating a sequence, but lacks the deliberation process: A generated sequence is directly used as final output without further polishing. However, deliberation is a common behavior in human's daily life like reading news and writing papers/articles/books. In this work, we introduce the deliberation process into the encoder-decoder framework and propose deliberation networks for sequence generation. A deliberation network has two levels of decoders, where the first-pass decoder generates a raw sequence and the second-pass decoder polishes and refines the raw sentence with deliberation. Since the second-pass deliberation decoder has global information about what the sequence to be generated might be, it has the potential to generate a better sequence by looking into future words in the raw sentence. Experiments on neural machine translation and text summarization demonstrate the effectiveness of the proposed deliberation networks. On the WMT 2014 English-to-French translation task, our model establishes a new state-of-the-art BLEU score of 41.5.

\[[PDF](https://papers.nips.cc/paper/6775-deliberation-networks-sequence-generation-beyond-one-pass-decoding.pdf)\] 
