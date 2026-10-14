---
layout: work
title: Research
slug: /research
items:

  - title: "(Ongoing Work) Generative AI-Assisted Response-Adaptive Factorial Designs"
    image:
      src: /assets/img/work/water.png
      alt: water
    description: >-
      This project proposes a generative AI-assisted, response-adaptive factorial design framework to identify effective combinations of health intervention components. By adaptively learning from participant responses and optimizing experimental allocation, the method aims to improve data efficiency while protecting vulnerable populations through in-silico experimentation. The framework supports personalized and resource-efficient evaluation of interventions in constrained settings. See <a href="https://drive.google.com/file/d/1plIBjZnj3FZfBzsz-aFgXsG13H42UUNp/view?usp=sharing">poster</a>.

  - title: "Budgeted Human Calibration for Modeling and Evaluation with Multiple AI Judges"
    image:
      src: /assets/img/work/sand.png
      alt: sand
    description: >-
      This project studies how to combine evaluations from multiple AI judges under a limited human-annotation budget. See <a href="https://arxiv.org/pdf/2607.16239">preprint</a>.

  - title: "TERRA: Transformer-Enabled Recursive R-Learner"
    image:
      src: /assets/img/work/sand.png
      alt: sand
    description: >-
      TERRA is a framework for estimating longitudinal heterogeneous treatment effects (HTEs) by combining the causal structure of structural nested mean models (SNMMs) with the representational power of Transformers. Many real-world settings—including clinical interventions, digital experimentation, and marketing attribution—involve repeated treatments over time, with carryover effects, time-varying heterogeneity, and post-treatment bias. Standard HTE methods are not designed for these challenges; TERRA is developed to address them. See <a href="https://arxiv.org/pdf/2510.22407">preprint</a>.

  - title: "Feature Importance and Selection in Language Models with Semi-Structured Data"
    image:
      src: /assets/img/work/water.png
      alt: water
    description: >-
      We study variable-group selection for serialized semi-structured inputs to improve efficiency and interpretability. The prompt is partitioned into predefined groups (e.g., demographics, genetics, and MRI features), each associated with a learnable scaling parameter between 0 and 1. Under sparsity-inducing regularization, unimportant feature groups can be replaced by special tokens such as ⟨PAD⟩, encouraging the model to focus on informative inputs while preserving predictive performance for Alzheimer's disease outcomes. To optimize the discrete selection mechanism, we use a two-stage smoothing strategy: first relaxing combinatorial selection to Bernoulli sampling, and then using a gradient estimator to approximate gradients through the discrete sampling step. See <a href="https://drive.google.com/file/d/1c0URrLS1bG3CEeeHPeeT_mlk1Kl5uCzL/view?usp=sharing">preprint</a>.

  - title: "An Enhanced Language Model for Predicting Amyloid Beta PET, Tau PET, and Cognitive Decline in Alzheimer's Disease"
    image:
      src: /assets/img/work/sand.png
      alt: sand
    description: >-
      We investigated different serialization strategies, including Markdown, plain text, feature-wise, and visit-wise formats, for representing longitudinal tabular data from ADNI, HABS-HD, and POINTER as LLM inputs. We used LoRA to fine-tune Llama 3 and Llama 3.1 for predicting Alzheimer's disease pathology and cognitive outcomes. Our developed model, ADLLM, outperforms existing machine-learning baselines in the external A4 cohort. See <a href="https://drive.google.com/file/d/1op2DfnIvFVvcp97THm4z6mDJiMP4MGxx/view?usp=sharing">preprint</a>.

  - title: "Enhanced Language Models for Predicting and Understanding HIV Care Disengagement: A Case Study in Tanzania"
    image:
      src: /assets/img/work/water.png
      alt: water
    description: >-
      We developed an enhanced large language model (LLM) fine-tuned on electronic medical records (EMRs) to predict individuals at risk of disengaging from HIV care in Tanzania. See <a href="https://www.nature.com/articles/s41746-026-02349-3">paper</a>.

  - title: "Mediation Analysis with Mendelian Randomization and Efficient Multiple-GWAS Integration"
    image:
      src: /assets/img/work/sand.png
      alt: sand
    description: >-
      We use structural equations to characterize relationships among exposure, mediator, and outcome effects based on a causal diagram. We develop a three-step procedure for mediation analysis that integrates multiple GWAS and uses joint rerandomization and Rao-Blackwellization to address <strong>measurement-error bias</strong>, <strong>winner's curse</strong>, <strong>loser's curse</strong>, and <strong>imperfect IV selection</strong>. See <a href="https://arxiv.org/abs/2312.10563">preprint</a>, <a href="https://github.com/LQRrrrr/MAGIC">code</a>, and <a href="https://github.com/LQRrrrr/MR.Rerand">package</a>.

  - title: "Theoretical Investigation of Mediation Analysis with Mendelian Randomization and Summary Data"
    image:
      src: /assets/img/work/water.png
      alt: water
    description: >-
      We provide a rigorous statistical analysis of two widely used frameworks for conducting mediation analysis with Mendelian randomization. See <a href="https://drive.google.com/file/d/1kk7PRwMGYdazYJ7uE_MpJzFosRn3mWxi/view">preprint</a>.

  - title: "Benchmarking QTL Pipelines, Including Isoform-QTL, eQTL, and Splicing-QTL Methods"
    image:
      src: /assets/img/work/sand.png
      alt: sand
    description: >-
      We compare the performance of RSEM, Kallisto, Cufflinks, Salmon + FastQTL, eQTL, and Leafcutter pipelines on simulated data. Our empirical results show that isoform-QTL pipelines outperform the alternatives in this benchmark, with Cufflinks achieving the strongest performance in terms of power and false discovery rate. See <a href="https://drive.google.com/file/d/1CQuQivzTD9LEZt5vPYFq9fZhVUDJVb_6/view?usp=sharing">slides</a> and <a href="https://drive.google.com/file/d/1lA5_GVSLwN1_4kTr3gwRKmqhUlx-Yqoa/view?usp=sharing">preprint</a>.

  - title: "GMS Training Framework and WMMLP"
    image:
      src: /assets/img/work/water.png
      alt: water
    description: >-
      We construct a weighted multiplicative multilayer perceptron (WMMLP) in PyTorch based on a Taylor expansion of M-estimators and use neural networks to solve M-estimation problems in bootstrap and cross-validation settings. See <a href="https://drive.google.com/file/d/1hN_bLWVfeioHlpYY2CtSDO2_Hv24f_6w/view?usp=sharing">final summer research report</a>.
---

If interested, please refer to <strong><a href="https://drive.google.com/file/d/1gYkYg-M2hl4wY1wHkQHMfP9AeYZhB7H4/view?usp=sharing">Qiuran's CV</a></strong> or contact me for more details.
<br />
<br />
