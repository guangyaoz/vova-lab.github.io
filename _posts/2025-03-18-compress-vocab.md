---
title: Compressed Vocabulary Expansion Makes Stronger Recommender Systems
author: Haochen Zhang
tags:
  - Large Language Model
  - Recommender System
  - Memory Efficiency
  - Vocabulary Expansion

---

Recommender systems play a pivotal role in providing relevant content to users. With the rapid development of large language models (LLMs), researchers have begun utilizing LLMs to build more powerful recommender systems. However, existing approaches that focus on aligning LLMs with recommendation tasks do not fully leverage their sequential information processing capabilities, leading to suboptimal performance.

In this paper, we propose a novel system called compressed vocabulary expansion where each item is assigned a unique ID within the expanded vocabulary. Our framework effectively capitalizes LLMs' sequence understanding abilities, significantly enhancing their performance on recommendation tasks. Additionally, to make end-to-end training feasible we compress the embedding layer, making our method practical for large-scale industrial applications. The effectiveness and performance of our method are demonstrated through comprehensive experiments on multiple large-scale recommendation datasets and comparisons with prior works.

Paper under review for ACL 2025.
