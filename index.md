---
layout: default
title: Jaber Chamak
---

I am Jaber Qezelbash Chamak, PhD, a **Data Scientist** and **ML/AI Engineer/Scientist** with 5+ years of hands-on experience.

- End-to-end ML workflows: data preparation, modeling, evaluation, and communication of results.
- Practical engineering skills with Python, SQL, Spark, Hive, Azure, AWS, Databricks, and Power BI.
- Applied deep learning and AI methods for classification, prediction, clinical decision support, and translation.
- Growing hands-on experience in LLMs, GenAI, and healthcare NLP / automation workflows.

---


---

### 1) RAG-Based IT Support Chatbot with Llama 3.1

<img src="{{ '/images/RAG_Llama_proj.png' | relative_url }}" alt="RAG-based multilingual IT support chatbot workflow" class="project-image">

- **Problem:** Customer-support chatbots can hallucinate or miss ticket-specific context when they rely only on fine-tuning.
- **What I built:** A RAG-first multilingual support chatbot using **Llama 3.1-8B-Instruct**, **BGE-M3 retrieval**, **BGE reranking**, and **FAISS**.
- **Highlights:**
  - train-only FAISS knowledge base built from solved support tickets,
  - RAG-grounded supervised fine-tuning data construction,
  - LoRA / QLoRA adapter fine-tuning,
  - retrieve → rerank → generate validation pipeline,
  - saved predictions, retrieved evidence, and evaluation metrics.
- **Why it matters:** Demonstrates an end-to-end GenAI workflow where retrieval, grounding, and fine-tuning work together for practical customer-support automation.
- **Tech stack:** Python, PyTorch, Hugging Face Transformers, PEFT / QLoRA, Llama 3.1, BGE-M3, FAISS, RAG.
- **Code:** [GitHub Repository](https://github.com/JaberQezelbash/RAG-finetune-Llama-3.1-8B-Instruct)


## Selected Projects

### 2) Medical Q&A LLM Fine-Tuning with Qwen2.5-1.5B-Instruct

<img src="{{ '/images/Qwen_proj.png' | relative_url }}" alt="Medical Q&A LLM fine-tuning workflow" class="project-image">

- **Problem:** Practical healthcare LLM experimentation is often limited by GPU availability and engineering overhead.
- **What I built:** A CPU-only LoRA fine-tuning workflow for **Qwen2.5-1.5B-Instruct** on a public medical Q&A dataset.
- **Highlights:**
  - parameter-efficient fine-tuning with LoRA,
  - prompt masking focused on assistant responses,
  - compatibility with Jupyter / IPykernel environments,
  - lightweight inference and evaluation notebooks,
  - base-vs-fine-tuned comparison and quick ROUGE-L sanity checks.
- **Why it matters:** Demonstrates practical LLM adaptation, reproducible experimentation, and healthcare-oriented GenAI prototyping under constrained compute.
- **Tech stack:** Python, PyTorch, Hugging Face Transformers, PEFT / LoRA, notebook-based evaluation.
- **Code:** [GitHub Repository](https://github.com/JaberQezelbash/finetune-Qwen2.5-1.5B-Instruct)

---

### 2) KANBalance

<img src="{{ '/images/KANBalance.svg' | relative_url }}" alt="KANBalance project figure" class="project-image">

- **Problem:** In many healthcare AI settings, the clinically important class is also the rarest class.
- **What I built:** **KANBalance**, a framework that combines **Kolmogorov-Arnold Networks (KANs)** with **Focal Loss** to improve learning under severe class imbalance.
- **Highlights:**
  - targets minority-class representation learning rather than relying only on resampling,
  - evaluated on imbalanced medical imaging tasks including chest X-ray and brain MRI classification,
  - includes ablation studies on learnable knots and loss design choices.
- **Why it matters:** This project is especially relevant for high-stakes ML where rare classes can have the highest operational or clinical importance.
- **Tech stack:** Python, PyTorch, medical imaging, deep learning, class-imbalance learning, model evaluation.
- **Code:** [GitHub Repository](https://github.com/JaberQezelbash/KANBalance)
- **Publication:** [Pattern Recognition (2026)](https://doi.org/10.1016/j.patcog.2025.112325)

---

### 3) DEQ-KAN

<img src="{{ '/images/DEQ-KAN.svg' | relative_url }}" alt="DEQ-KAN project figure" class="project-image">

- **Problem:** Deep medical image models often face a tradeoff between expressive depth, memory use, and training stability.
- **What I built:** **DEQ-KAN**, a framework that combines **Deep Equilibrium Models (DEQs)** with **Kolmogorov-Arnold Networks (KANs)** for robust image classification.
- **Highlights:**
  - implicit infinite-depth modeling through fixed-point iteration,
  - KAN-based edge functions for more flexible and interpretable representations,
  - applied to tasks such as pneumonia detection, brain tumor classification, and histopathology analysis.
- **Why it matters:** Demonstrates advanced model design for accuracy, efficiency, and robustness in medical imaging workflows.
- **Tech stack:** Python, PyTorch, DEQs, KANs, CNN feature extraction, medical image classification.
- **Code:** [GitHub Repository](https://github.com/JaberQezelbash/DEQ-KAN)
- **Publication:** [Biomedical Signal Processing and Control (2025)](https://doi.org/10.1016/j.bspc.2025.108087)

---

### 4) NoPropBalance

<img src="{{ '/images/NoPropBalance.svg' | relative_url }}" alt="NoPropBalance project figure" class="project-image">

- **Problem:** Extreme class imbalance can remain difficult even when using standard oversampling or cost-sensitive learning approaches.
- **What I built:** **NoPropBalance**, a memory-friendly imbalance-mitigation pipeline that extends no-propagation learning with minority-focused reconstruction and refinement stages.
- **Highlights:**
  - class-weighted latent denoising,
  - minority-class decoder for image reconstruction,
  - hinge-GAN refinement,
  - balanced downstream classifier training.
- **Why it matters:** This project explores an alternative training strategy for imbalance mitigation that is modular and potentially attractive in compute-constrained environments.
- **Tech stack:** Python, deep learning, image generation / refinement, class-imbalance mitigation.
- **Code:** [GitHub Repository](https://github.com/JaberQezelbash/NoPropBalance)

---


## Skills

- **MLOps** and **LLMOps**
- **Programming:** Python, SQL, R, MATLAB, C++
- **Cloud / Data:** Azure, AWS, Databricks, Spark, Hive
- **ML / AI:** predictive modeling, deep learning, medical imaging, time-series modeling, class-imbalance learning, LLM fine-tuning
- **Business / research communication:** model evaluation, reporting, presentation of technical work to mixed audiences

