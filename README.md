# Table of Contents

Introduction to DM2-ND repositories (*Data Mining towards Decision Making* Laboratory [\[page\]](http://www.meng-jiang.com/lab.html) at the University of Notre Dame).

Director: Dr. Meng Jiang [\[page\]](http://www.meng-jiang.com/)

**Chapter 1. Graph Machine Learning**
- **1.1. Learning Graph Dynamics** 
  - **CalendarGNN** [\[lab repo\]](https://github.com/DM2-ND/CalendarGNN)
    - **Paper:** *Calendar Graph Neural Networks for Modeling Time Structures in Spatiotemporal User Behaviors* (**KDD 2020**) [\[download\]](http://www.meng-jiang.com/pubs/calendargnn-kdd20/calendargnn-kdd20-paper.pdf)
    - **Leading author:** Daheng Wang (dwang8@nd.edu)
    - **Usage:** Given user behavior data (e.g., reading behaviors on News App), can we learn user representations that preserve spatiotemporal patterns of a variety of periodicity (e.g., hourly, weekly, and weekday patterns)? The representations can be used for demongraphic prediction (sex, age, etc.) and recommendation.
    - **Novelty:** It leverages the Calendar System as a knowledge graph to enhance graph neural networks on temporal graph data of user behaviors.
- **1.2. Graph Anomaly Detection** 
  - **1.2.1. AOO** [\[lab repo\]](https://github.com/DM2-ND/AOO)
    - **Paper:** *Actionable Objective Optimization for Suspicious Behavior Detection on Large Bipartite Graphs* (**BigData 2018**) [\[download\]](https://tzhao.io/files/papers/BigData18-aoo.pdf)
    - **Leading author:** Tong Zhao (tzhao2@nd.edu)
    - **Usage:** Given "who-reviews-what" data on e-commercial platforms, can we deliver an automated solution to accurately suspend fake reviewers and/or bully buyers?
    - **Novelty:** This model learns to measure the suspiciousness of nodes by simultaneously minimizing the loss (e.g., false reviews) and maximizing the profit (e.g., sales).
  - **1.2.2. GAL** [\[lab repo\]](https://github.com/DM2-ND/GAL) [\[src repo\]](https://github.com/zhao-tong/Graph-Anomaly-Loss)
    - **Paper:** *Error-Bounded Graph Anomaly Loss for GNNs* (**CIKM 2020**) [\[download\]](https://dl.acm.org/doi/pdf/10.1145/3340531.3411979)
    - **Leading author:** Tong Zhao (tzhao2@nd.edu)
    - **Usage:** Can we learn node representations in an *unsupervised* way on bipartite graphs for the tasks of outlier detection or dense block detection?
    - **Novelty:** This model uses unsupervised graph anomaly detection algorithms to produce pseudo labels to supervise graph neural network frameworks.

**Chapter 2. Information Extraction** 
- **2.1. Scientific Named Entity Recognition (SciNER)** 
  - **TriTrain** [\[lab repo\]](https://github.com/DM2-ND/TriTrain) [\[src repo\]](https://github.com/QingkaiZeng/TriTrain)
    - **Paper:** *Tri-Train: Automatic Pre-Fine Tuning between Pre-Training and Fine-Tuning for SciNER* (**EMNLP 2020**) [\[download\]](https://www.aclweb.org/anthology/2020.findings-emnlp.429.pdf)
    - **Leading author:** Qingkai Zeng (qzeng@nd.edu)
    - **Usage:** Given a sentence "FDA has approved remdesivir for the treatment of COVID-19 in certain situations", can we detect "FDA: Organization", "remdesivir: Drug", and "COVID-19: disease"? This framework performs NER in scientific domains.
    - **Novelty:** It introduces a "pre-fine tuning" step between pre-training and fine-tuning to fast and effectively adapt NER models in new scientific domains.
- **2.2. XXX** 
  - **XXX** [\[lab repo\]](https://github.com/DM2-ND/XXX) [\[src repo\]](https://github.com/)
    - **Paper:** *XXX* (**XXX 20XX**) [\[download\]](https://XXX)
    - **Leading author:** XXX (XXX@nd.edu)
    - **Usage:** XXX
    - **Novelty:** XXX

**Chapter 3. Natural Language Generation**
- **3.1. Methodlogies** 
  - **KENLG-Reading** [\[lab repo\]](https://github.com/DM2-ND/KENLG-Reading) [\[src repo\]](https://github.com/wyu97/KENLG-Reading)
    - **Paper:** *A Survey of Knowledge-enhanced Text Generation* (**arXiv**) [\[download\]](https://arxiv.org/abs/2010.04389)
    - **Leading author:** Wenhao Yu (wyu1@nd.edu)
    - **Usage:** It offers a long reading list to complement with the survey paper. Related literature in 2020-2021 has been added and discussed.
    - **Novelty:** Enhancing natural language generation (NLG) with knowledge is a very popular research direction. However, there was not a comprehensive survey.
- **3.2. Question Answering** 
  - **CrossVAE** [\[lab repo\]](https://github.com/DM2-ND/CrossVAE)
    - **Paper:** *Crossing Variational Autoencoders for Answer Retrieval* (**ACL 2020**) [\[download\]](https://www.aclweb.org/anthology/2020.acl-main.498/)
    - **Leading author:** Wenhao Yu (wyu1@nd.edu)
    - **Usage:** Given a question and a set of answer candidates, can we accurately retrieve the best answer?
    - **Novelty:** This model learns across two Variational Auto-Encoders that (a) generates answer from question and (b) generate question from answer, in order to better understand question/answer semantics.
