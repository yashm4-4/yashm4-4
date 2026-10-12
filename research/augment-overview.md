
# Protein Machine Learning & Scientific Engineering

**Augment Biologics | Applied Machine Learning Researcher / Consultant**  
*December 2025 – Present*

My work at Augment Biologics focuses on developing machine learning and computational modeling workflows for protein engineering. I have contributed to protein language model adaptation, rigorous evaluation, inference optimization, and scalable molecular modeling infrastructure, with an emphasis on building computational tools that are both scientifically reliable and practical for research applications.

---

## 1. Protein Language Models for Antibody Glycosylation Prediction

**Objective:** Adapt pretrained protein language models for antibody glycosylation prediction while improving model generalization and computational efficiency.

I developed Python/PyTorch workflows for fine-tuning **ESM2 (650M)** using **Low-Rank Adaptation (LoRA)**.

### Key Contributions

- Developed training and inference pipelines for protein sequence modeling and glycosylation prediction.
- Designed **protein-disjoint data splits** and held-out evaluation procedures to reduce the risk of data leakage and assess generalization.
- Conducted **70+ model runs** to compare configurations, investigate validation behavior, and evaluate predictive performance.
- Optimized site-centered sequence context, achieving comparable predictive performance at approximately **5.5× lower inference cost** for the longest tested sequences.
- Supported systematic model comparison and evaluation to inform downstream protein-variant prioritization.

### Technical Focus

`Python` `PyTorch` `ESM2` `LoRA` `Protein Language Models` `Model Evaluation` `Inference Optimization`

**Key Takeaway:** This work combined protein representation learning with careful experimental evaluation and computational optimization, emphasizing the importance of reliable predictions and efficient model deployment.

---

## 2. Scalable Molecular Modeling with Rosetta

**Objective:** Develop reliable computational infrastructure for evaluating protein variants using Rosetta-based stability calculations.

I engineered high-throughput molecular modeling workflows capable of screening **25,000+ antibody Fc variants**.

### Key Contributions

- Developed Python-based workflows for evaluating predicted protein stability changes using **Rosetta ΔΔG calculations**.
- Adapted molecular modeling pipelines for scalable cloud execution using **Modal** and **AWS S3**.
- Implemented reproducible batch processing and automated failure-recovery mechanisms.
- Organized computational results for downstream analysis and interpretation by research collaborators.
- Improved workflow reliability and reduced the need for manual intervention during large-scale screening.

### Technical Focus

`Python` `Rosetta` `Protein Stability` `Molecular Modeling` `Modal` `AWS S3` `Cloud Computing` `Workflow Automation`

**Key Takeaway:** This work strengthened my experience translating computational molecular modeling methods into scalable scientific software that supports protein engineering research.

---

## 3. Research & Engineering Approach

Across these projects, I have focused on three complementary aspects of computational research:

1. **Biological relevance:** Connecting computational modeling approaches to meaningful protein engineering questions.
2. **Scientific rigor:** Designing evaluations that distinguish genuine predictive improvements from artifacts of data partitioning or experimental setup.
3. **Engineering reliability:** Building reproducible, computationally efficient workflows that can support large-scale research applications.

My broader interests lie at the intersection of protein representation learning, computational molecular design, and scientific software engineering.

---

## Research Availability

This page summarizes my individual technical contributions at Augment Biologics.

The underlying company source code, datasets, model weights, proprietary protein designs, internal configurations, and unpublished experimental results are not publicly available.

The results described here concern computational modeling and engineering. They do not imply independent experimental validation of the screened protein designs.
