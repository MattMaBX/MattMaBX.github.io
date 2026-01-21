---
title: "Multi-Granularity Dual-Aware Contrastive Learning for Few-shot Named Entity Recognition"
collection: publications
category: conferences
permalink: /publication/ma2024multi
date: 2024-06-30
venue: '2024 International Joint Conference on Neural Networks (IJCNN)'
paperurl: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10651079'
citation: 'Ma B, Wang C, Guo S, et al. Multi-Granularity Dual-Aware Contrastive Learning for Few-shot Named Entity Recognition[C]//2024 International Joint Conference on Neural Networks (IJCNN). IEEE, 2024: 1-8.'
---

Few-shot Named Entity Recognition aims to identify named entities from unstructured texts in various domains using a minimal amount of training samples and classify them into predefined categories. Many popular approaches decompose this process into two tasks: Span Detection and Entity Classification. However, they still have some issues: (1) Neglecting presentation optimization. Most of these methods emphasize classification, neglecting the optimization of span presentation during Span Detection. (2) Missing label semantics. They have not fully leveraged semantic information of entity type labels during Entity Classification. To address these issues, this paper proposes Multi-Granularity Dual-Aware Contrastive Learning (MGDAC) for few-shot NER. Specifically, we introduce multi-granularity contrastive learning for solve neglecting presentation optimization, focusing on both the overall vector and internal vector granularity to enhance features beneficial for span detection in token vector representations. Additionally, we design dual-aware contrastive learning for solve missing label semantics, effectively utilizing semantic information from both entity tokens and entity type labels during prototype construction to jointly optimize prototype representations. Finally, extensive experiments on the FewNERD dataset demonstrate that our proposed method exhibits improvements in both Span Detection and Entity Classification, outperforming other competitive baseline methods.