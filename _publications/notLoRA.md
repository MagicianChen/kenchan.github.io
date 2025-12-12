---
title: "Not All LoRA Parameters Are Essential: Insights on Inference Necessity"
collection: preprint
category: preprint
permalink: /publication/notLoRA
excerpt: 'Chen, Guanhua, et al. "Not All LoRA Parameters Are Essential: Insights on Inference Necessity." arXiv preprint arXiv:2503.23360 (2025).'
date: 2025-03-30
venue: 'arXiv'
paperurl: 'https://arxiv.org/pdf/2503.23360'
---

Current research on LoRA primarily focuses on minimizing the number of fine-tuned parameters or optimizing its architecture. However, the necessity of all fine-tuned LoRA layers during inference remains underexplored. In this paper, we investigate the contribution of each LoRA layer to the model’s ability to predict the ground truth and hypothesize that lower-layer LoRA modules play a more critical role in model reasoning and understanding. To address this, we propose a simple yet effective method to enhance the performance of large language models (LLMs) fine-tuned with LoRA. Specifically, we identify a “boundary layer” that distinguishes essential LoRA layers by analyzing a small set of validation samples. During inference, we drop all LoRA layers beyond this boundary. We evaluate our approach on three strong baselines across four widely-used text generation datasets. Our results demonstrate consistent and significant improvements, underscoring the effectiveness of selectively retaining critical LoRA layers during inference.
