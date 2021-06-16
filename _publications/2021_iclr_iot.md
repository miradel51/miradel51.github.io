---
title: "IOT: Instance-wise Layer Reordering for Transformer Structures "
collection: publications
permalink: /publication/2021_iclr_iot
excerpt: ''
date: 2021-05-04
author: Jinhua Zhu*, <b>Lijun Wu</b>*, Yingce Xia, Shufang Xie, Tao Qin, Wengang Zhou, Houqiang Li, Tie-Yan Liu
conference: In Ninth International Conference on Learning Representations <b>(ICLR-2021)</b> (*=equal contribution)
venue: ''
paperurl: 'https://openreview.net/pdf?id=ipUPfYxWZvM'
citation: '<br>
@inproceedings{zhu2021iot,<br>
title={IOT: Instance-wise Layer Reordering for Transformer Structures},<br>
author={Jinhua Zhu and Lijun Wu and Yingce Xia and Shufang Xie and Tao Qin and Wengang Zhou and Houqiang Li and Tie-Yan Liu},<br>
booktitle={International Conference on Learning Representations},<br>
year={2021},<br>
}'

---
<h2><strong>Abstract</strong></h2>
With sequentially stacked self-attention, (optional) encoder-decoder attention, and
feed-forward layers, Transformer achieves big success in natural language processing (NLP), and many variants have been proposed. Currently, almost all these
models assume that the layer order is fixed and kept the same across data samples.
We observe that different data samples actually favor different orders of the layers.
Based on this observation, in this work, we break the assumption of the fixed layer
order in Transformer and introduce instance-wise layer reordering into model structure. Our Instance-wise Ordered Transformer (IOT) can model variant functions by
reordered layers, which enables each sample to select the better one to improve the
model performance under the constraint of almost same number of parameters. To
achieve this, we introduce a light predictor with negligible parameter and inference
cost to decide the most capable and favorable layer order for any input sequence.
Experiments on 3 tasks (neural machine translation, abstractive summarization,
and code generation) and 9 datasets demonstrate consistent improvements of our
method. We further show that our method can also be applied to other architectures
beyond Transformer. Our code is released at Github.

\[[PDF](https://openreview.net/pdf?id=ipUPfYxWZvM)\]  \[[CODE](https://github.com/instance-wise-ordered-transformer/IOT)\]