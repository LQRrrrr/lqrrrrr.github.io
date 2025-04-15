---
layout: work
title: Research
slug: /research
items:
  - title: (Ongoing work) LLM Feature Selection
    image:
      src: /assets/img/work/water.png
      alt: water
    description: We propose a method that fine-tunes LLMs to pinpoint key input variables. We partition the prompt into predefined groups (e.g., demographics, genetics, MRI features), each with a learnable scaling parameter (0–1). Under sparsity-inducing regularization (L1 or entropy), unimportant features are replaced by special tokens (⟨PAD⟩), ensuring the model focuses on clinically impactful data while preserving predictive fidelity for AD outcomes.
    
  - title: (Ongoing work) Generative AI Assisted Response Adaptive Factorial Designs
    image:
      src: /assets/img/work/sand.png
      alt: water
    description: This project proposes a generative AI-assisted, response-adaptive factorial design framework to identify the most effective combinations of health intervention components. By adaptively learning from participant responses and optimizing experimental allocation, the method efficiently identifies impactful strategies while protecting vulnerable populations through in-silico experimentation. The design enables personalized, ethical, and data-efficient evaluation of interventions in resource-constrained settings. See <a href="https://drive.google.com/file/d/1plIBjZnj3FZfBzsz-aFgXsG13H42UUNp/view?usp=sharing"> poster</a>.
  
  - title: (Ongoing work) AI-driven generative digital twins cohort to emulate communication and behavioral dynamics in real-world ADRD patients
    image:
      src: /assets/img/work/water.png
      alt: sand
    description: We built a platform for digital twins trained by video capturing different symptoms, in terms of linguistic, emotional, and behavioral nuances that typify ADRD. Our aims are (1) mimicking the real-world interaction between caregivers and ADRD patients; (2) providing better caregiver training; and (3) doing experimentation on created digital twins. We also aim to validate the created digital twins to provide trustworthy results. See the current <a href="https://mr-thomas-chat.onrender.com/"> Platform</a>.  

   
  - title: An Enhanced Language Model for Predicting Alzheimer's Disease Pathology
    image:
      src: /assets/img/work/sand.png
      alt: sand
    description: We investigated different serialized ways (e.g. Markdown, plain text, feature-wise, and visit-wise) for longitudinal tabular data from ADNI, HABS-HD, and POINTER as LLM inputs and used LORA to finetune Llama 3 and Llama 3.1 tailored to Alzheimer’s disease pathology outcomes prediction. Our developed model is referred to as ADLLM and outperforms existing ML models in external A4 cohorts. See <a href="https://drive.google.com/file/d/1op2DfnIvFVvcp97THm4z6mDJiMP4MGxx/view?usp=sharing"> preprint</a>. 

  - title: Mediation Analysis with Mendelian Randomization and Efficient Multiple GWAS Integration.
    image:
      src: /assets/img/work/water.png
      alt: water
    description: We used structural equations to construct the relationship between the mediator, exposure, and outcome effect based on the causal diagram. A three-step procedure was designed for conducting mediation analysis with integrated multiple GWAS using joint rerandomization and Rao-blackwellization to eliminate the <strong>measurement error bias</strong>, <strong>the winner's curse</strong>, <strong>the loser's curse</strong>, and <strong>the imperfect IV selection issue</strong>. See <a href="https://arxiv.org/abs/2312.10563"> preprint</a>, links to <a href="https://github.com/LQRrrrr/MAGIC"> code </a> and <a href="https://github.com/LQRrrrr/MR.Rerand"> package </a>.

  - title: On the Theoretical Investigation of Mediation Analysis with Mendelian Randomization and Summary Data.
    image:
      src: /assets/img/work/sand.png
      alt: sand
    description: We provide rigorous statistical analysis of existing two popular frameworks for conducting mediation analysis with Mendelian Randomization. See <a href="https://drive.google.com/file/d/1kk7PRwMGYdazYJ7uE_MpJzFosRn3mWxi/view"> preprint </a>.

  - title: Benchmark of different QTL pipelines (including isoform-QTL, eQTL, and splicing-QTL).
    image:
      src: /assets/img/work/water.png
      alt: sand
    description: We compared the performance of RSEM, Kallisto, Cufflinks, Salmon + FastQTL, eQTL, and Leafcutter on the simulated dataset. We empirically demonstrated that isoform-QTL pipelines outperform all others. Among all isoform-QTL pipelines, Cufflinks has the best performance in terms of power and false discovery rate. See <a href="https://drive.google.com/file/d/1CQuQivzTD9LEZt5vPYFq9fZhVUDJVb_6/view?usp=sharing"> slides </a> and <a href="https://drive.google.com/file/d/1lA5_GVSLwN1_4kTr3gwRKmqhUlx-Yqoa/view?usp=sharing"> preprint </a> .

  - title: GMS training framework and WMMLP.
    image:
      src: /assets/img/work/sand.png
      alt: sand
    description: We constructed the weighted multiplicative MLP (WMMLP) in PyTorch based on Taylor expansion of M estimators and used neural networks to solve the M-estimation problem under the bootstrap and cross-validation context. See <a href="https://drive.google.com/file/d/1hN_bLWVfeioHlpYY2CtSDO2_Hv24f_6w/view?usp=sharing"> final summer research report</a>.
---

If interested, please refer to <strong><a href="https://drive.google.com/file/d/14lfZb2gs07HBZ0rZgvlOOajTkZU57icl/view?usp=sharing" target="_blank">Qiuran's CV</a></strong> or contact me for more details.
<br />
<br />
