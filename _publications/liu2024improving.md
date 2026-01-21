---
title: "Improving Implicit Discourse Relation Recognition via Connective Prediction and Dependency-weighted Label Hierarchy"
collection: publications
category: conferences
permalink: /publication/liu2024improving
date: 2024-06-30
venue: '2024 International Joint Conference on Neural Networks (IJCNN)'
paperurl: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10650647'
citation: 'Liu X, Guo S, Li J, Su X, Ma B, et al. Improving Implicit Discourse Relation Recognition via Connective Prediction and Dependency-weighted Label Hierarchy[C]//2024 International Joint Conference on Neural Networks (IJCNN). IEEE, 2024: 1-8.'
---

Implicit discourse relation recognition aims to identify logical relations between two arguments without explicit connectives and is a challenging task in discourse analysis. Recent methods tend to leverage the label hierarchy to enhance discourse relation representations. However, they fail to fully utilize the connective information. Specifically, the methods overlook the guiding role of connectives in discourse relation classification by treating them as the last-level labels in the label hierarchy to leverage connective information, whereas it would be more appropriate to exploit connective information prior to relation classification. Moreover, these methods ignore the dependency degree of labels between different levels in the label hierarchy. In other words, they consider the label hierarchy as an unweighted undirected graph, and assume that the path weights between high-level labels and their corresponding low-level labels are the same, which leads to an insufficient construction of the label hierarchy. To overcome these issues, we propose a method for implicit discourse relation recognition (IDRR) utilizing Connective Prediction and Dependency-weighted Label Hierarchy (CP-DLH). Experimental results on PDTB 2.0 dataset show that our model achieves the state-of-the-art performance at all hierarchical levels.