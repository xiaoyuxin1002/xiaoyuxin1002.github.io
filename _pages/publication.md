---
layout: archive
title: ""
permalink: /publication/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

During Ph.D.
======

* **In the Name of Fairness: Assessing the Bias in Clinical Record De-identification** <br>
  <u>Yuxin Xiao</u>\*, Shulammite Lim\*, Tom Joseph Pollard, Marzyeh Ghassemi. <br>
  [FAccT 2023] (Oral Presentation) <br>
  <details> 
    <summary>
        Abstract |
        <a href="https://arxiv.org/pdf/2305.11348.pdf" role="button" target="_blank"> Paper </a> | 
        <a href="https://github.com/xiaoyuxin1002/bias_in_deid" role="button" target="_blank"> Code </a>
    </summary>
    Data sharing is crucial for open science and reproducible research, but the legal sharing of clinical data requires the removal of protected health information from electronic health records. This process, known as de-identification, is often achieved through the use of machine learning algorithms by many commercial and open-source systems. While these systems have shown compelling results on average, the variation in their performance across different demographic groups has not been thoroughly examined. In this work, we investigate the bias of de-identification systems on names in clinical notes via a large-scale empirical analysis. To achieve this, we create 16 name sets that vary along four demographic dimensions: gender, race, name popularity, and the decade of popularity. We insert these names into 100 manually curated clinical templates and evaluate the performance of nine public and private de-identification methods. Our findings reveal that there are statistically significant performance gaps along a majority of the demographic dimensions in most methods. We further illustrate that de-identification quality is affected by polysemy in names, gender context, and clinical note characteristics. To mitigate the identified gaps, we propose a simple and method-agnostic solution by fine-tuning de-identification methods with clinical context and diverse names. Overall, it is imperative to address the bias in existing methods immediately so that downstream stakeholders can build high-quality systems to serve all demographic parties fairly.
  </details>  

Before Ph.D.
======

* **Uncertainty Quantification with Pre‑trained Language Models: A Large‑Scale Empirical Analysis** <br>
  <u>Yuxin Xiao</u>, Paul Pu Liang, Umang Bhatt, Willie Neiswanger, Ruslan Salakhutdinov, Louis-Philippe Morency. <br>
  [EMNLP 2022] (Findings) <br>
  <details> 
    <summary>
        Abstract |
        <a href="https://arxiv.org/pdf/2210.04714.pdf" role="button" target="_blank"> Paper </a> | 
        <a href="https://github.com/xiaoyuxin1002/UQ-PLM" role="button" target="_blank"> Code </a>
    </summary>
    Pre-trained language models (PLMs) have gained increasing popularity due to their compelling prediction performance in diverse natural language processing (NLP) tasks. When formulating a PLM-based prediction pipeline for NLP tasks, it is also crucial for the pipeline to minimize the calibration error, especially in safety-critical applications. That is, the pipeline should reliably indicate when we can trust its predictions. In particular, there are various considerations behind the pipeline: (1) the choice and (2) the size of PLM, (3) the choice of uncertainty quantifier, (4) the choice of fine-tuning loss, and many more. Although prior work has looked into some of these considerations, they usually draw conclusions based on a limited scope of empirical studies. There still lacks a holistic analysis on how to compose a well-calibrated PLM-based prediction pipeline. To fill this void, we compare a wide range of popular options for each consideration based on three prevalent NLP classification tasks and the setting of domain shift. In response, we recommend the following: (1) use ELECTRA for PLM encoding, (2) use larger PLMs if possible, (3) use Temp Scaling as the uncertainty quantifier, and (4) use Focal Loss for fine-tuning.
  </details>  
  
* **SAIS: Supervising and Augmenting Intermediate Steps for Document-Level Relation Extraction** <br>
  <u>Yuxin Xiao</u>, Zecheng Zhang, Yuning Mao, Carl Yang, Jiawei Han. <br>
  [NAACL 2022] (Oral Presentation) <br>
  <details> 
    <summary>
        Abstract |
        <a href="https://arxiv.org/pdf/2109.12093.pdf" role="button" target="_blank"> Paper </a> | 
        <a href="https://github.com/xiaoyuxin1002/SAIS" role="button" target="_blank"> Code </a>
    </summary>
    Stepping from sentence-level to documentlevel, the research on relation extraction (RE) confronts increasing text length and more complicated entity interactions. Consequently, it is more challenging to encode the key information sources—relevant contexts and entity types. However, existing methods only implicitly learn to model these critical information sources while being trained for RE. As a result, they suffer the problems of ineffective supervision and uninterpretable model predictions. In contrast, we propose to explicitly teach the model to capture relevant contexts and entity types by Supervising and Augmenting Intermediate Steps (SAIS) for RE. Based on a broad spectrum of carefully designed tasks, our proposed SAIS method not only extracts relations of better quality due to more effective supervision, but also retrieves the corresponding supporting evidence more accurately so as to enhance interpretability. By assessing model uncertainty, SAIS further boosts the performance via evidence-based data augmentation and ensemble inference while reducing the computational cost. Eventually, SAIS delivers state-of-the-art RE results on three benchmarks (DocRED, CDR, and GDA) and outperforms the runner-up by 5.04% relatively in F1 score in evidence retrieval on DocRED.
  </details>
  
* **Amortized Auto-Tuning: Cost-Efficient Transfer Optimization for Hyperparameter Recommendation** <br>
  <u>Yuxin Xiao</u>, Eric P. Xing, Willie Neiswanger. <br>
  [arXiv 2021] (Preprint) <br>
  <details> 
    <summary>
        Abstract |
        <a href="https://arxiv.org/pdf/2106.09179.pdf" role="button" target="_blank"> Paper </a> | 
        <a href="https://github.com/xiaoyuxin1002/amortized-auto-tuning" role="button" target="_blank"> Code </a>
    </summary>
    With the surge in the number of hyperparameters and training times of modern machine learning models, hyperparameter tuning is becoming increasingly expensive. However, after assessing 40 tuning methods systematically, we find that each faces certain limitations. In particular, methods that speed up tuning via knowledge transfer typically require the final performance of hyperparameters and do not focus on low-fidelity information. As we demonstrate empirically, this common practice is suboptimal and can incur an unnecessary use of resources. It is more cost-efficient to instead leverage low-fidelity tuning observations to measure inter-task similarity and transfer knowledge from existing to new tasks accordingly. However, performing multi-fidelity tuning comes with its own challenges in the transfer setting: the noise in additional observations and the need for performance forecasting. Therefore, we propose and conduct a thorough analysis of a multi-task multi-fidelity Bayesian optimization framework, which leads to the best instantiation—AmorTized Auto-Tuning (AT2). We further present an offline-computed 27-task Hyperparameter Recommendation (HyperRec) database to serve the community. Extensive experiments on HyperRec and other real-world databases illustrate the effectiveness of our AT2 method.
  </details>
  
* **Heterogeneous Network Representation Learning: A Unified Framework with Survey and Benchmark** <br>
  Carl Yang\*, <u>Yuxin Xiao</u>\*, Yu Zhang\*, Yizhou Sun, Jiawei Han. <br>
  [TKDE Journal 2020] (200+ Citations, 270+ GitHub Stars and Forks) <br>
  <details> 
    <summary>
        Abstract |
        <a href="https://arxiv.org/pdf/2004.00216.pdf" role="button" target="_blank"> Paper </a> | 
        <a href="https://github.com/yangji9181/HNE" role="button" target="_blank"> Code </a>
    </summary>
    Since real-world objects and their interactions are often multi-modal and multi-typed, heterogeneous networks have been widely used as a more powerful, realistic, and generic superclass of traditional homogeneous networks (graphs). Meanwhile, representation learning (a.k.a. embedding) has recently been intensively studied and shown effective for various network mining and analytical tasks. In this work, we aim to provide a unified framework to deeply summarize and evaluate existing research on heterogeneous network embedding (HNE), which includes but goes beyond a normal survey. Since there has already been a broad body of HNE algorithms, as the first contribution of this work, we provide a generic paradigm for the systematic categorization and analysis over the merits of various existing HNE algorithms. Moreover, existing HNE algorithms, though mostly claimed generic, are often evaluated on different datasets. Understandable due to the application favor of HNE, such indirect comparisons largely hinder the proper attribution of improved task performance towards effective data preprocessing and novel technical design, especially considering the various ways possible to construct a heterogeneous network from real-world application data. Therefore, as the second contribution, we create four benchmark datasets with various properties regarding scale, structure, attribute/label availability, and etc. from different sources, towards handy and fair evaluations of HNE algorithms. As the third contribution, we carefully refactor and amend the implementations and create friendly interfaces for 13 popular HNE algorithms, and provide all-around comparisons among them over multiple tasks and experimental settings. By putting all existing HNE algorithms under a unified framework, we aim to provide a universal reference and guideline for the understanding and development of HNE algorithms. Meanwhile, by open-sourcing all data and code, we envision to serve the community with an ready-to-use benchmark platform to test and compare the performance of existing and future HNE algorithms.
  </details>
  
* **Discovering Strategic Behaviors for Collaborative Content-Production in Social Networks** <br>
  <u>Yuxin Xiao</u>, Adit Krishnan, Hari Sundaram. <br>
  [WWW 2020] (Oral Presentation) <br>
  <details> 
    <summary>
        Abstract |
        <a href="https://arxiv.org/pdf/2003.03670.pdf" role="button" target="_blank"> Paper </a> | 
        <a href="https://github.com/CrowdDynamicsLab/Discovering_Strategic_Behaviors" role="button" target="_blank"> Code </a>
    </summary>
    Some social networks provide explicit mechanisms to allocate social rewards such as reputation based on users’ actions, while the mechanism is more opaque in other networks. Nonetheless, there are always individuals who obtain greater rewards and reputation than their peers. An intuitive yet important question to ask is whether these successful users employ strategic behaviors to become influential. It might appear that the influencers "have gamed the system." However, it remains difficult to conclude the rationality of their actions due to factors like the combinatorial strategy space, inability to determine payoffs, and resource limitations faced by individuals. The challenging nature of this question has drawn attention from both the theory and data mining communities. Therefore, in this paper, we are motivated to investigate if resource-limited individuals discover strategic behaviors associated with high payoffs when producing collaborative/interactive content in social networks. We propose a novel framework of Dynamic Dual Attention Networks (DDAN) which models individuals’ content production strategies through a generative process, under the influence of social interactions involved in the process. Extensive experimental results illustrate the model’s effectiveness in user behavior modeling. We make three strong empirical findings: (1) Different strategies give rise to different social payoffs; (2) The best performing individuals exhibit stability in their preference over the discovered strategies, which indicates the emergence of strategic behavior; and (3) The stability of a user’s preference is correlated with high payoffs.
  </details>
  
* **Non-local Attention Learning on Large Heterogeneous Information Networks** <br>
  <u>Yuxin Xiao</u>\*, Zecheng Zhang\*, Carl Yang, Chengxiang Zhai. <br>
  [IEEE BigData 2020] (Oral Presentation) <br>
  <details> 
    <summary>
        Abstract |
        <a href="https://xiaoyuxin1002.github.io/files/NLAH.pdf" role="button" target="_blank"> Paper </a> | 
        <a href="https://github.com/xiaoyuxin1002/NLAH" role="button" target="_blank"> Code </a>
    </summary>
    Heterogeneous information network (HIN) summarizes rich structural information in real-world datasets and plays an important role in many big data applications. Recently, graph neural networks have been extended to the representation learning of HIN. One very recent advancement is the hierarchical attention mechanism which incorporates both node-wise and semantic-wise attention. However, since HIN is more likely to be densely connected given its diverse types of edges, repeatedly applying graph convolutional layers can make the node embeddings indistinguishable very quickly. In order to avoid oversmoothness, existing graph neural networks targeting HIN generally suffer from a shallow structure. Consequently, those approaches ignore information beyond the local neighborhood. This design flaw violates the concept of non-local learning, which emphasizes the importance of capturing long-range dependencies. To properly address this limitation, we propose a novel framework of non-local attention in heterogeneous information networks (NLAH). Our framework utilizes a non-local attention structure to complement the hierarchical attention mechanism. In this way, it leverages both local and non-local information simultaneously. Moreover, a weighted sampling schema is designed for NLAH to reduce the computation cost for large-scale datasets. Extensive experiments on three different real-world heterogeneous information networks illustrate that our framework exhibits extraordinary scalability and outperforms state-of-the-art baselines with significant margins.
  </details>
