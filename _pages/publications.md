---
layout: single
title: "Publications"
permalink: /publications/
author_profile: true
---

## Accepted / Published

**When More Parameters Hurt: Foundation Model Priors Amplify Worst-Client Disparity Under Extreme Federated Heterogeneity**  
Kiran Naseer, Umar Shoaib  
*FL@FM Workshop, IJCAI–ECAI 2026, Bremen, Germany · August 2026*  
[arXiv:2605.08992](https://arxiv.org/abs/2605.08992) · **Accepted & Presented**

> Foundation-model priors (DistilBERT+LoRA) show a 50.1% worst-client accuracy gap under extreme heterogeneity (α=0.1) vs. 32.2% for a task-specific baseline (TextCNN). Establishes worst-client accuracy as a primary evaluation criterion in federated NLP.

---

## Under Review

**Perplexity Predicts Protection: Choosing Pretrained Backbones for Worst-Client Fairness in Federated Parameter-Efficient Fine-Tuning**  
Kiran Naseer, Samreen Azhar, Umar Shoaib, Haroon Mahmood, Muhammad Awais  
*MDPI Electronics (Special Issue: Federated Learning and Its Application) · Manuscript electronics-4562418*  
[arXiv:2609.23463](https://arxiv.org/abs/2609.23463) · **Revision complete — awaiting editor decision**

> Backbone-selection rule requiring no federated training: ranking candidates by per-word masked-LM perplexity reproduces the ranking of worst-client benefit across three datasets (Spearman ρ = −0.867, 9 cells). 313 pre-registered runs. Full run manifest, committed predictions and deviation log publicly released.

---

**MedFL-Stress: A Statistically Rigorous Privacy-Aware Robustness Benchmark for Federated Brain Tumour Segmentation Under Cross-Hospital MRI Heterogeneity**  
Naveed Anwer Butt, Kiran Naseer, Rana Muhammad Zail Ul Abideen, Samreen Azhar, Nagwan Abdel Samee, Imran Ashraf  
*Journal of Magnetic Resonance Imaging (JMRI) · Manuscript JMRI-26-1740*  
[arXiv:2605.09025](https://arxiv.org/abs/2605.09025) · **Under review**

> Five-seed confidence intervals, differential-privacy analysis and membership-inference resistance across FedAvg, FedProx, FedBN, SCAFFOLD and FedNova on BraTS 2020. Key finding: method choice changes *who* benefits, not just the average.

---

**Reassessing Global Gradient-Norm Imbalance in BLIP Fine-Tuning Across Physical Domains**  
Kiran Naseer, Samreen Azhar, Dwarikanath Mahapatra (Khalifa University, UAE)  
*IEEE Transactions on Multimedia (Regular Paper) · Manuscript MM031554*  
[arXiv:2609.23655](https://arxiv.org/abs/2609.23655) · **Under review**

> Multi-seed staged fine-tuning protocol reducing training instability under severe physical domain shift across underwater, aerial and radiological imaging domains (BLEU-4 = 0.292 ± 0.012 on UICD). Identifies global gradient-norm imbalance as the primary instability driver.

---

## In Preparation

**Adaptive ROI-Aware Active Learning for Label-Efficient Glioma MRI Segmentation: Ground-Truth-Free Annotation Windowing**  
Kiran Naseer, Essam Rashed (University of Hyogo, Japan)  
*Target venue: TBD*

> ROI-aware Borda-fusion active learning with ET-proportional adaptive annotation window and ground-truth-free proxy cold start (UNet2D, GT correlation 0.945). UCSF-PDGM experiments complete (validation Dice 0.8689); BraTS 2023 cross-validation in progress.

---

## arXiv Preprints

All preprints openly accessible:

- [arXiv:2605.08992](https://arxiv.org/abs/2605.08992) — When More Parameters Hurt (A1, accepted FL@FM IJCAI–ECAI 2026)
- [arXiv:2609.23463](https://arxiv.org/abs/2609.23463) — Perplexity Predicts Protection (B1, under review MDPI Electronics)
- [arXiv:2605.09025](https://arxiv.org/abs/2605.09025) — MedFL-Stress (B2, under review JMRI)
- [arXiv:2609.23655](https://arxiv.org/abs/2609.23655) — Reassessing Gradient-Norm Imbalance in BLIP (B3, under review IEEE TMM)

---

## Code & Reproducibility

All primary research code, pre-registered run manifests, committed prediction intervals, and deviation logs are publicly released at [github.com/KiranNaseer-AI](https://github.com/KiranNaseer-AI).
