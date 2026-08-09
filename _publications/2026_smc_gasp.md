---
title: "GASP: Graph-Augmented Soft Prompt Tuning for Few-Shot Text Classification"
collection: 
permalink: /publication/2026_smc_gasp
excerpt: ''
date: 2026-06-16
author: Sen Zhang, <b>Mieradilijiang Maimaiti</b>*, and Wushour Silamu
conference: In IEEE International Conference on Systems, Man, and Cybernetics <b>(IEEE SMC,2026)</b> (*=corresponding author)
venue: ''
paperurl: 'https://www.researchgate.net/publication/412045419_GASP_Graph-Augmented_Soft_Prompt_Tuning_for_Few-Shot_Text_Classification'
citation: '<br>
@inproceedings{zheng2026_gasp,<br>
  title={GASP: Graph-Augmented Soft Prompt Tuning for Few-Shot Text Classification},<br>
  author={Sen Zhang, Mieradilijiang Maimaiti, and Wushour Silamu},<br>
  journal={IEEE SMC},<br>
  year={2026},<br>
}'

---
<h2><strong>Abstract</strong></h2>
Few-shot short text classification (STC) is challenging due to semantic sparsity and limited labeled supervision. 
Existing STC methods often alleviate sparsity by exploiting corpus-level structure, for example, through document/word graphs or additional objectives such as contrastive learning; however, these designs can increase pipeline complexity and training overhead. 
Soft prompt tuning is a lightweight and parameter-efficient alternative, yet it is typically sequence-based and does not explicitly leverage word co-occurrence structure. 
We propose GRAPHPROMPT, a soft prompt tuning method that incorporates a word co-occurrence graph by using a WORDGCN module to compute graph-informed representations, transforming them into continuous prompt embeddings, and prepending them to the input of a BERT classifier. 
Compared with graph-based STC methods, GRAPHPROMPT does not require document-level graphs or multi-stage training objectives; compared to vanilla soft prompts, it injects graph-derived information into the prompt embeddings. 
Experiments on six datasets under a unified 20-shot protocol (20 training and 20 validation instances per class) over five random splits show that GRAPHPROMPT consistently outperforms a graph-only WORDGCN baseline and standard soft prompt tuning, and yields additional gains over strong BERT-only tuning on sparse domains, 
while incurring only modest overhead relative to vanilla soft prompts.

\[[PDF](https://www.researchgate.net/publication/412045419_GASP_Graph-Augmented_Soft_Prompt_Tuning_for_Few-Shot_Text_Classification)\]
