---
title: "A Two-Stage Prediction-Aware Contrastive Learning Framework for Multi-Intent NLU"
collection: publications
category: conferences
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'Guanhua Chen, Yutong Yao, Derek F. Wong, and Lidia S. Chao. 2024. A Two-Stage Prediction-Aware Contrastive Learning Framework for Multi-Intent NLU. In Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024), pages 1778–1788, Torino, Italia. ELRA and ICCL.'
date: 2024-05-05
venue: 'COLING(2024)'
paperurl: '[http://academicpages.github.io/files/paper3.pdf](https://aclanthology.org/2024.lrec-main.157.pdf)'
---

Multi-intent natural language understanding (NLU) presents a formidable challenge due to the model confusion arising from multiple intents within a single utterance. While previous works train the model contrastively to increase the margin between different multi-intent labels, they are less suited to the nuances of multi-intent NLU. They ignore the rich information between the shared intents, which is beneficial to constructing a better embedding space, especially in low-data scenarios. We introduce a two-stage Prediction-Aware Contrastive Learning (PACL) framework for multi-intent NLU to harness this valuable knowledge. Our approach capitalizes on shared intent information by integrating word-level pre-training and prediction-aware contrastive fine-tuning. We construct a pre-training dataset using a word-level data augmentation strategy. Subsequently, our framework dynamically assigns roles to instances during contrastive fine-tuning while introducing a prediction-aware contrastive loss to maximize the impact of contrastive learning. We present experimental results and empirical analysis conducted on three widely used datasets, demonstrating that our method surpasses the performance of three prominent baselines on both low-data and full-data scenarios.
