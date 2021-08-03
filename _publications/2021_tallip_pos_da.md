---
title: "Improving the Data Augmentation for Low-Resource NMT Guided by POS-Tagging and Paraphrase Embedding"
collection: publications
permalink: /publication/2021_tallip_pos_da
excerpt: ''
date: 2021-05-02
author: <b>Mieradilijiang Maimaiti</b>, Yang Liu*, Huanbo Luan, Zegao Pan, and Maosong Sun
conference: In ACM Transactions on Asian and Low-Resource Language Information Processing <b>(ACM TALLIP, 2021)</b> (*=corresponding author)
venue: ''
paperurl: ''
citation: ''

---
<h2><strong>Abstract</strong></h2>
Data augmentation is an approach for several text generation tasks. Generally, in the machine translation paradigm, mainly in low-resource language scenarios, many data augmentation methods have been proposed. The most used approaches for generating pseudo data mainly lay in word omission, random sampling, or replacing some words in the text. However, previous methods barely guarantee the quality of augmented data. In this work, we try to build the data by using paraphrase embedding and POS-Tagging. Namely, we generate the fake monolingual corpus by replacing the main four POS-Tagging labels, such as noun, adjective, adverb, and verb based on both the paraphrase table and their similarity. We select the bigger corpus size of the paraphrase table with word-level and obtain the word embedding of each word in the table, then calculate the cosine similarity between these words and tagged words in the original sequence. In addition, we exploit the ranking algorithm to choose highly similar words to reduce semantic errors and leverage the POS-Tagging replacement to mitigate syntactic error to some extent. Experimental results show that our augmentation method consistently outperforms all the previous SOTA methods on the low-resource language pairs in 7 language pairs from 4 corpora by 1.16 ~ 2.39 BLEU points.

\[[PDF (preprint)](https://miradel51.github.io/files/tallip2021_pos_da.pdf)\]  
