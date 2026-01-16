---
permalink: /
title: "PIK3CA-Mutant and Wild-Type Endometrial Cancer’s Comparative Interactomics Analysis Using STRING PPI Networks and TCGA–GTEx Expression."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

PIK3CA mutations are among the most common
genetic changes associated with endometrial carcinoma (EC),
the most prevalent gynecological cancer. Despite proteogenomic
studies revealing novel markers such as MYC activity and
PIK3R1 in-frame insertion-deletion, protein-protein interaction
(PPI) networks between PIK3CA-mutant and wild-type endome-
trial cancers have not been extensively compared to healthy
endometrium. Here, we combine transcriptome data from GTEx
normal uterus and TCGA-UCEC tumors, use MC3 mutation
calls to stratify tumors according on PIK3CA mutation status,
and use STRING v12 to create condition-specific PPI networks.
We demonstrate how PIK3CA mutations rewire the tumor
interactome through differential expression, hub shift analysis,
hub shift analysis, community detection, and functional enrich-
ment. Wild-type tumors show networks centered on receptor
tyrosine kinases (such as EGFR/ERBB2) and mixed signaling
modules, while PIK3CA-mutant tumors have networks centered
on AKT/mTOR and mitotic regulators (specifically AURKA,
PLK1). These results expand previous PIK3CA interactome
research in other malignancies to endometrial cancer and reveal
possible mutation-specific vulnerabilities.

Haematological Disorders Classification from CBC Data using Autoencoder Enhanced Semi-Supervised Learning with Ensemble Techniques and XAI.
======
Accurate interpretation of the Complete Blood
Count (CBC) information is essential to the diagnosis of hema-
tologic disorders, but manual analysis is time-consuming, sub-
jective, and somewhat difficult in resource-constrained clinical
circumstances. This paper suggests a multi-class classification of
hematological disorders with routinely available CBC parame-
ters using an end-to-end autoencoder-enhanced semi-supervised
learning model. The architecture incorporates domain-aware
feature engineering, graph-based semi-supervised label spread-
ing, autoencoder-based latent feature learning, and a stacked
ensemble classifier.
A 1,281 CBC sample labeled dataset of 9 diagnostic categories
is boosted with 654 unlabeled CBC reports via high-confidence
pseudo-labeling to make good use of real-world unlabeled data.
The nonlinear feature representations are trained through an
auto-encoder and are trained together with clinically meaningful
ratios and indices. The stacked ensemble, based on Random
Forest, Extra Trees, Support Vector Machine, Logistic regression,
Gradient Boosting, and XGBoost, is used to perform classifica-
tion; however, averaging of seeds is conducted to make it stronger.
The SMOTE Tomek resampling is used to deal with class imbal-
ance, and the problem of poor predictions by high-confidence
elements is solved through clinically inspired adjustments of
the rule-based prediction. Model performance is measured on
a strictly held-out test basis in terms of discrimination, calibra-
tion, and interpretability measures. The presented methodology
demonstrates an accuracy of 94.94, balanced accuracy of 0.93,
and macro-averaged ROC-AUC of 0.98, and the probability
estimates are well-calibrated. Explanations using SHAP ensure
that dependencies on physiologically significant characteristics
like platelet count, hemoglobin level, and white blood cell indices
are relied upon.
The findings show that semi-supervised learning, representa-
tion learning, and ensemble modeling can be used to effectively,
interpretably, and scalably diagnose hematological diseases in
multiple classes with conventional CBC data, which can be
implemented in a clinical decision support system in routine and
low-resource clinical environments.

<!-- For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting -->

Two-Stage Noise-Reduced Pneumonia Detection in Chest X-Ray Images Using Denoising Autoencoder–CNN Integration
======
Pneumonia remains a major cause of morbidity and
mortality worldwide, with chest X-ray imaging serving as a
primary tool for early diagnosis. However, the presence of noise,
artifacts, and low-quality acquisitions significantly degrades im-
age interpretability and limits the effectiveness of automated deep
learning–based detection systems. Conventional convolutional
neural networks (CNNs) are particularly sensitive to such degra-
dations, leading to reduced classification reliability. To address
this limitation, we propose a hybrid deep learning framework
that integrates a denoising autoencoder (DAE) with a CNN for
robust pneumonia detection from chest X-ray images. The DAE
is trained to reconstruct clean images from noisy inputs, enabling
the suppression of noise while preserving diagnostically relevant
features, and is subsequently coupled with a CNN classifier in a
unified pipeline. The proposed model is evaluated on the publicly
available Kaggle chest X-ray dataset using data augmentation,
class-weighted loss, and early stopping to mitigate class imbalance
and overfitting. Experimental results demonstrate that the DAE-
CNN framework consistently outperforms a CNN-only baseline,
achieving an accuracy of 92.9%, an F1-score of 94.6%, and a
balanced accuracy of 90.9%, compared to 86.1% accuracy and
an F1-score of 89.8% obtained without denoising. These results
highlight the effectiveness of incorporating learnable denoising
into deep learning pipelines and underscore its potential for
improving the robustness and reliability of automated pneumonia
detection in clinical imaging scenarios.
