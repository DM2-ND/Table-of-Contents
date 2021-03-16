# Table of Contents

Introduction to DM2-ND repositories (*Data Mining towards Decision Making* Laboratory [\[page\]](http://www.meng-jiang.com/lab.html) at the University of Notre Dame).

Director: Dr. Meng Jiang [\[page\]](http://www.meng-jiang.com/)

**Chapter 1. Graph Machine Learning**
- **1.1. Learning Graph Dynamics** 
  - **1.1.1. CalendarGNN** [\[lab repo\]](https://github.com/DM2-ND/CalendarGNN)
    - **Paper:** *Calendar Graph Neural Networks for Modeling Time Structures in Spatiotemporal User Behaviors* (**KDD 2020**) [\[download\]](http://www.meng-jiang.com/pubs/calendargnn-kdd20/calendargnn-kdd20-paper.pdf)
    - **Leading author:** Daheng Wang (dwang8@nd.edu)
    - **Usage:** Given user behavior data (e.g., reading behaviors on News App), can we learn user representations that preserve spatiotemporal patterns of a variety of periodicity (e.g., hourly, weekly, and weekday patterns)? The representations can be used for demongraphic prediction (sex, age, etc.) and recommendation.
    - **Novelty:** It leverages the Calendar System as a knowledge graph to enhance graph neural networks on temporal graph data of user behaviors.
- **1.2. Learning Node Complementarity**
  - **1.2.1. LearnSuc** [\[lab repo\]](https://github.com/DM2-ND/Learnsuc)
    - **Paper:** *Multi-Type Itemset Embedding for Learning Behavior Success* (**KDD 2018**) [\[download\]](http://www.meng-jiang.com/pubs/learnsuc-kdd18/learnsuc-kdd18-paper.pdf)
    - **Leading author:** Daheng Wang (dwang8@nd.edu)
    - **Usage:** Can we learn the representations of elements in a set by preserving their complementarity?
    - **Novelty:** It proposes a novel representation learning method for sets of items of different types.
  - **1.2.2. TUBE** [\[lab repo\]](https://github.com/DM2-ND/TUBE)
    - **Paper:** *TUBE: Embedding Behavior Outcomes for Predicting Success* (**KDD 2019**) [\[download\]](http://www.meng-jiang.com/pubs/tube-kdd19/tube-kdd19-paper.pdf)
    - **Leading author:** Daheng Wang (dwang8@nd.edu)
    - **Usage:** Can we learn the complementarity among researchers for effective teaming?
    - **Novelty:** It proposes a novel measurement of complementarity to replace similarity in representation learning frameworks.
- **1.3. Graph Anomaly Detection** 
  - **1.3.1. AOO** [\[lab repo\]](https://github.com/DM2-ND/AOO)
    - **Paper:** *Actionable Objective Optimization for Suspicious Behavior Detection on Large Bipartite Graphs* (**BigData 2018**) [\[download\]](https://tzhao.io/files/papers/BigData18-aoo.pdf)
    - **Leading author:** Tong Zhao (tzhao2@nd.edu)
    - **Usage:** Given "who-reviews-what" data on e-commercial platforms, can we deliver an automated solution to accurately suspend fake reviewers and/or bully buyers?
    - **Novelty:** This model learns to measure the suspiciousness of nodes by simultaneously minimizing the loss (e.g., false reviews) and maximizing the profit (e.g., sales).
  - **1.3.2. GAL** [\[lab repo\]](https://github.com/DM2-ND/GAL) [\[src repo\]](https://github.com/zhao-tong/Graph-Anomaly-Loss)
    - **Paper:** *Error-Bounded Graph Anomaly Loss for GNNs* (**CIKM 2020**) [\[download\]](https://dl.acm.org/doi/pdf/10.1145/3340531.3411979)
    - **Leading author:** Tong Zhao (tzhao2@nd.edu)
    - **Usage:** Can we learn node representations in an *unsupervised* way on bipartite graphs for the tasks of outlier detection or dense block detection?
    - **Novelty:** This model uses unsupervised graph anomaly detection algorithms to produce pseudo labels to supervise graph neural network frameworks.
- **1.4. Graph Data Augmentation** 
  - **1.4.1. GAug** [\[lab repo\]](https://github.com/DM2-ND/GAug) [\[src repo\]](https://github.com/zhao-tong/GAug)
    - **Paper:** *Data Augmentation for Graph Neural Networks* (**AAAI 2021**) [\[download\]](https://arxiv.org/pdf/2006.06830.pdf)
    - **Leading author:** Tong Zhao (tzhao2@nd.edu)
    - **Usage:** How can we perform graph data augmentation for graph neural networks (GNNs) in the context of improving semi-supervised node-classification?
    - **Novelty:** It shows that neural edge predictors can effectively encode classhomophilic structure to promote intra-class edges and demote inter-class edges in given graph structure, and introduces a novel framework that leverages these insights to improve performance in GNN-based node classification via edge prediction.

**Chapter 2. Information Extraction (IE)** 
- **2.1. Scientific Named Entity Recognition (SciNER)** 
  - **2.1.1. TriTrain** [\[lab repo\]](https://github.com/DM2-ND/TriTrain) [\[src repo\]](https://github.com/QingkaiZeng/TriTrain)
    - **Paper:** *Tri-Train: Automatic Pre-Fine Tuning between Pre-Training and Fine-Tuning for SciNER* (**EMNLP 2020**) [\[download\]](https://www.aclweb.org/anthology/2020.findings-emnlp.429.pdf)
    - **Leading author:** Qingkai Zeng (qzeng@nd.edu)
    - **Usage:** Given a sentence "FDA has approved remdesivir for the treatment of COVID-19 in certain situations", can we detect "FDA: Organization", "remdesivir: Drug", and "COVID-19: disease"? This framework performs NER in scientific domains.
    - **Novelty:** It introduces a "pre-fine tuning" step between pre-training and fine-tuning to fast and effectively adapt NER models in new scientific domains.
- **2.2. IE from Tabular Data**
  - **2.2.1. Tablepedia** [\[lab repo\]](https://github.com/DM2-ND/Tablepedia)
    - **Paper:** *Experimental Evidence Extraction in Data Science with Hybrid Table Features and Ensemble Learning* (**WWW 2020**) [\[download\]](https://wyu97.github.io/papers/C2_WWW_2020.pdf)
    - **Leading author:** Wenhao Yu (wyu1@nd.edu)
    - **Usage:** Can we discover knowledge from tables of experimental results in data science literature? It offers a new data set and a tool.
    - **Novelty:** It extracts experimental evidences from data science papers in PDF format and builds up the first experimental database for related research.
  - **2.2.2. TCN**
    - **Paper:** *TCN: Table Convolutional Network for Web Table Interpretation* (**WWW 2021**) [\[download\]](https://arxiv.org/abs/2102.09460)
    - **Leading author:** Daheng Wang (dwang8@nd.edu)
    - **Usage:** Can we extract information from semi-structured webpages provides valuable long-tailed facts for augmenting knowledge graph?
    - **Novelty:** It is a novel relational table representation learning approach considering both the intra- and inter-table contextual information.

**Chapter 3. Natural Language Generation (NLG)**
- **3.1. Methodlogies** 
  - **3.1.1. KENLG-Reading** [\[lab repo\]](https://github.com/DM2-ND/KENLG-Reading) [\[src repo\]](https://github.com/wyu97/KENLG-Reading)
    - **Paper:** *A Survey of Knowledge-enhanced Text Generation* (**arXiv**) [\[download\]](https://arxiv.org/abs/2010.04389)
    - **Leading author:** Wenhao Yu (wyu1@nd.edu)
    - **Usage:** It offers a long reading list to complement with the survey paper. Related literature in 2020-2021 has been added and discussed.
    - **Novelty:** Enhancing NLG with knowledge is a very popular research direction. However, there was not a comprehensive survey.
- **3.2. Question Answering** 
  - **3.2.1. CrossVAE** [\[lab repo\]](https://github.com/DM2-ND/CrossVAE)
    - **Paper:** *Crossing Variational Autoencoders for Answer Retrieval* (**ACL 2020**) [\[download\]](https://www.aclweb.org/anthology/2020.acl-main.498/)
    - **Leading author:** Wenhao Yu (wyu1@nd.edu)
    - **Usage:** Given a question and a set of answer candidates, can we accurately retrieve the best answer?
    - **Novelty:** This model learns across two Variational Auto-Encoders that (a) generates answer from question and (b) generate question from answer, in order to better understand question/answer semantics.
