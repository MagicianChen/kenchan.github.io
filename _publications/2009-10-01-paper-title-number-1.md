---
title: "Multi-level curriculum learning for multi-turn dialogue generation"
collection: publications
category: manuscripts
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'G. Chen, R. Zhan, D. F. Wong and L. S. Chao, "Multi-Level Curriculum Learning for Multi-Turn Dialogue Generation," in IEEE/ACM Transactions on Audio, Speech, and Language Processing, vol. 31, pp. 3958-3967, 2023, doi: 10.1109/TASLP.2023.3322583.'
date: 2023-10-06
venue: 'TASLP(2023)'
paperurl: '[http://academicpages.github.io/files/paper1.pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10273589)'
---

Since deep learning is the dominant paradigm in the multi-turn dialogue generation task, large-scale training data is the key factor affecting the model performance. To make full use of the training data, the existing work directly applied curriculum learning to the multi-turn dialogue generation task, training model in a “easy-to-hard” way. But the design of the current methodology does not consider dialogue-specific features. To close this gap, we propose a Multi-Level Curriculum Learning (MLCL) method for multi-turn dialogue generation by considering the word-level linguistic feature and utterance-level semantic relation in a dialogue. The motivation is that word-level knowledge is beneficial to understanding complex utterance-level dependency of dialogue. Thus, we design two difficulty measurements and a self-adaptive curriculum scheduler, making the model gradually shift the learning focus from word-level to utterance-level information during the training process. We also verify the independence and complementarity of the two measurements at different levels. We evaluate the performance on two widely used multi-turn dialogue datasets, and the results demonstrate that our proposed method outperforms the strong baselines and existing CL methods in terms of automated metrics and human evaluation. 
