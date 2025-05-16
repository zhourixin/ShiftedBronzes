# ShiftedBronzes
ShiftedBronzes is a benchmark designed to evaluate Out-of-Distribution (OOD) detection in specialized, fine-grained domains with multiple degrees of distributional shift. This repository contains the dataset loading code, evaluation metrics including the proposed DAD metric, and links to representative baseline methods.

---

## 📘 Overview

Out-of-distribution (OOD) detection in specialized domains with fine-grained classes remains a significant challenge due to subtle distribution shifts that substantially degrade model performance. 

Existing benchmarks either:
- evaluate multiple, coarse-grained shift levels on general-purpose datasets (e.g., near-OOD & far-OOD), or
- examine limited shift levels in fine-grained settings (e.g., open-set recognition),  

…but none comprehensively address **multi-level, fine-grained shift within specialized domains**.

To bridge this gap, **ShiftedBronzes** provides:
- A hierarchical fine-grained OOD benchmark with multiple shift levels
- A novel **distribution-aware degree (DAD)** metric to measure OOD sensitivity
- A study of representative **post-hoc** and **VLM-based** methods with tailored background-bias mitigation

---

## 📁 Repository Structure
ShiftedBronzes/
├── data/ # Data loading and structure definition
├── metrics/ # DAD metric implementation
├── scripts/ # Example usage and evaluation scripts
├── requirements.yaml # Environment specification
└── README.md
