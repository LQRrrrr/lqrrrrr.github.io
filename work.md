---
layout: work
title: Work
slug: /work
items:
  - title: Causal Mediation Analysis with Mendelian Randomization and Summary Data
    image:
      src: /assets/img/work/water.png
      alt: water
    description: We used structural equation to construct the relationship between mediator, exposure, and outcome effect based on
the causal diagram. A three-step procedure is designed for conducting mediation analysis with integrated multiple GWAS using joint
rerandomization and rao-blackwellization to eliminate the winner’s curse. We also empirically demonstrated the unbiasedness of proposed framework. I am  proving the asymptotic property of the direct and indirect effect estimators, and using the delta method to construct the valid standard errors of the mediating effect.
  - title: Mendelian Randomization with Summary Data
    image:
      src: /assets/img/work/sand.png
      alt: sand
    description: We empirically demonstrated the winner’s curse for MR estimators caused by LD clumping and showed the better
performance of proposed revised LD pruning in terms of lower standard errors and no winner’s curse. We also empirically demonstrated rerandomization and rao-blackwellization can reduce bias for thirteen popular Mendelian Randomization estimators and proved the asymptotic property of Inverse Variance Weighting and debiased IVW estimator with the adjustment
for common confounder.
  - title: Benchmark of different isoform quantification methods
    image:
      src: /assets/img/work/sand.png
      alt: sand
    description: We conducted analysis using isofrom quantification abundance QTL and splicing QTL methods in GTEx real data, used negative binomial, dirichelet distribution, and multinomial logit regression model to fit real TPM proportion data, and simulated data starting from short-read RNA-seq data. Performance of rsem, kallisto, cufflinks, salmon on simulated dataset were compared and we empirically demonstrated
rsem has the worst performance in terms of power and false discovery rate.
  - title: GMS training framework and WMMLP
    image:
      src: /assets/img/work/sand.png
      alt: sand
    description: We constructed the weighted multiplicative MLP (WMMLP) in PyTorch based on taylor expansion of M estimators and used neural networks to solve M-estimation problem under the bootstrap and cross validation context. I reviewed literatures related to neural network theory, neural control variable for variance reduction and function approximation and empirically demonstrated the low variance of estimators under the proposed WMMLP. Also, we implemented, tested, and documented different training and testing results on CIFAR10 and simulated dataset.
---



<br />
<br />
