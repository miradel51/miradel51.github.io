---
title: "Research on Neural Machine Translation Methods under Low-Resource Conditions"
collection: publications
permalink: /publication/2021_phd_thesis
excerpt: ''
date: 2021-05-01
author: <b>Mieradilijiang Maimaiti</b>
conference: Phd Thesis <b>(2021)</b> 
venue: ''
paperurl: 'https://kns.cnki.net/kcms2/article/abstract?v=3uoqIhG8C447WN1SO36whLpCgh0R0Z-i16_wNaYct1rCckkTLVqOrb5k-zqjznpcQN32DXhcsleZZocA6nBZtPtZZvGyDgV4&uniplatform=NZKPT'
citation: '<br>
@inproceedings{m.maimaiti2021_phdthesis,<br>
  title={Research on Neural Machine Translation Methods under Low-Resource Conditions},<br>
  author={Mieradilijiang Maimaiti},<br>
  booktitle={Phd Thesis},<br>
  year={2021},<br>
}'


---
<h2><strong>Abstract</strong></h2>
Machine translation (MT) is an important and challenging task in the research field
of natural language processing (NLP). Among various methods for machine translation,
neural machine translation (NMT) is the fastest growing and the most popular translation
method. NMT relies on massive parallel corpora, and thus it is diﬀicult to train an NMT
model with good generalization ability in low-resource settings. Therefore, there is an
urgent need to develop NMT models with better performance in low-resource settings.
However, some problems still exist: (1) How to implement a word segmentation system
with better performance to aid MT for low-resource languages; (2) How to eﬀiciently use
high-resourcelanguagestohelplow-resourcelanguages; (3)Howtogeneratepseudo-data
with higher quality. The research results in our thesis are summarized as follows:

**Augmenting Chinese word segmentation with self-supervision for low-resource
NMT.** Word segmentation has been considered as the core basic research in NLP. A Chi-
nese word segmentation (CWS) model with better performance can further improve the
performance of NMT in low-resource settings. Recent state-of-the-art methods based on
neural networks and pre-trained models have achieved great results. However, previous
works focus on training the models with static data, and therefore exploiting noisy data is
necessary for validating the robustness of CWS models. In this work, we propose a sim-
ple and effective self-supervised CWS approach based on the revised masked language
model and improved minimum risk training. Experimental results show that our approach
achieves significant improvements on openly available CWS datasets.

**Low-resource NMT method based on transferlearning.** Therearemanyexcellent
techniques in the research field of low-resource NMT. Recently, transfer learning (TL)
has been widely used in low-resource NMT. However, the original TL is neither able to
makefulluseofhighlyrelatedmultiplehigh-resourcelanguages. Toaddressthisproblem,
we present a multi-round transfer learning approach and a unified transliteration method.
Besides, considering that the model cannot learn information about the child model when
training the parent model, we propose a mixed transfer learning method. Experimental
results show that these two ideas achieve significant improvements on openly available
datasets.

**Low-resource NMT method based on data augmentation.** Data augmentation (DA) is a ubiquitous approach for several text generation tasks. 
Especially in the research field of low-resource NMT, many DA methods have been proposed. 
However, previous methodsbarelyguarantee the qualityof pseudo-data. In thiswork, weaugment the corpus
by constrained sampling method and build an evaluation sub-model to reduce grammar
errors to some extent. Besides, we also try to build pseudo-data using paraphrase tables
and POS-taggings, which also mitigates grammar errors in pseudo-data. Experimental
results show that these two ideas achieve significant improvements on openly available
datasets.

\[[Postgraduate Thesis](https://miradel51.github.io/files/phd_thesis.caj) Chinese Paper\] 
