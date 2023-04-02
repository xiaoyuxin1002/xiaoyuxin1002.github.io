---
layout: archive
title: ""
permalink: /publication/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Prior to Ph.D.
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