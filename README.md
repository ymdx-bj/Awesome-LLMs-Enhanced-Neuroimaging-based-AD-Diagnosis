# Neuroimaging-based Alzheimer’s Disease Diagnosis Powered with Large Language Models

## 📌 Introduction

Alzheimer’s disease (AD) is a progressive and irreversible neurodegenerative disorder. Early and accurate diagnosis is essential for timely intervention and treatment planning. Neuroimaging can capture subtle brain alterations, including cortical thinning, brain atrophy, and pathological protein deposition, before the onset of clinical symptoms.

Recent advances in large language models (LLMs) have enabled multimodal clinical data integration, interpretable diagnostic reasoning, and flexible orchestration of medical analysis tools. This repository accompanies the review paper **“Neuroimaging-based Alzheimer’s Disease Diagnosis Powered with Large Language Models”** and provides a structured collection of studies, datasets, and resources related to LLM-powered neuroimaging-based AD diagnosis.

All included studies are organized according to the functional roles of LLMs in the AD diagnosis workflow.

## 📄 Paper

**Title:** Neuroimaging-based Alzheimer’s Disease Diagnosis Powered with Large Language Models  
**Authors:** Yan Zhao et al.  
**Institution:** University of Shanghai for Science and Technology; Beijing Normal University; The University of Sydney  
**Link:** Coming soon

## 💎 Table of Contents

  * [📌 Introduction](#-introduction)
  * [📄 Paper](#-paper)
  * [✨ Highlights](#-highlights)
  * [🏗️ Taxonomy of LLM Roles](#️-taxonomy-of-llm-roles)
  * [🧠 Key Topics](#-key-topics)
  * [🗂️ Datasets](#️-datasets)
  * [📖 Papers](#-papers)
  * [🔍 Review Scope](#-review-scope)
  * [📥 Citation](#-citation)
  * [📢 Contributing](#-contributing)
  * [📧 Contact](#-contact)

## ✨ Highlights

  * Provides a comprehensive review of LLM-powered neuroimaging-based AD diagnosis.
  * Summarizes the use of sMRI, fMRI, PET, SPECT, clinical assessments, biomarkers, genetic information, and demographic data.
  * Proposes a taxonomy based on the core functional roles of LLMs: representation learning, clinical reasoning, and agent orchestration.
  * Organizes existing studies by imaging modality, input format, LLM architecture, dataset, task, and diagnostic performance.
  * Discusses technical, clinical, interpretability, safety, ethical, and translational challenges.

## 🏗️ Taxonomy of LLM Roles

The reviewed methods are grouped according to how LLMs participate in the AD diagnosis pipeline:

  * **Representation Learning:** LLMs or multimodal LLMs encode neuroimaging features, clinical information, and structured biomedical data.
  * **Clinical Reasoning:** LLMs generate diagnostic predictions, explanations, rationales, and disease-related inferences from multimodal evidence.
  * **Agent Orchestration:** LLM-based agents coordinate specialized models, tools, datasets, and subtasks to support flexible multimodal diagnosis.

## 🧠 Key Topics

### 1️⃣ Representation Learning

  * LLM-based neuroimaging feature encoding
  * Multimodal vision-language alignment
  * Semantic rephrasing of imaging-derived features
  * Knowledge generation and knowledge-guided representation learning
  * Tabular and structured clinical data representation

### 2️⃣ Clinical Reasoning

  * Multimodal clinical reasoning
  * Prompt-generated diagnostic rationales
  * Chain-of-Thought and reasoning-aware diagnosis
  * Knowledge-enhanced prediction
  * Interpretable AD classification and progression prediction

### 3️⃣ Agent Orchestration

  * Tool-augmented medical reasoning
  * Multimodal neuroimaging analysis agents
  * Self-learning and critical-agent frameworks
  * Multi-agent collaboration
  * Flexible task assignment and outcome aggregation

## 🗂️ Datasets

### Public Datasets

  * [Alzheimer’s Disease Neuroimaging Initiative (ADNI)](http://adni.loni.usc.edu/)
  * [Quantitative Templates for the Progression of AD (QT-PAD)](https://www.pi4cs.org/qt-pad-challenge)
  * [Open Access Series of Imaging Studies (OASIS)](https://sites.wustl.edu/oasisbrains/)
  * [Australian Imaging, Biomarker & Lifestyle (AIBL)](https://aibl.org.au/)
  * [National Alzheimer’s Coordinating Center (NACC)](https://www.naccdata.org/)
  * [Minimal Interval Resonance Imaging in Alzheimer’s Disease (MIRIAD)](https://www.ucl.ac.uk/brain-sciences/ion/research/research-centres/dementia-research-centre/research-clinical-trials/minimal-interval-resonance-imaging-alzheimers-disease-miriad)
  * [Alzheimer’s Brain MRI (AB-MRI)](https://www.kaggle.com/datasets/preetpalsingh25/alzheimers-dataset-4-class-of-images)
  * [Latin American Brain Health Institute (BrainLat)](https://brainlat.uai.cl/)
  * [Neuroimaging Initiative for Frontotemporal Lobar Degeneration(NIFD)](https://ida.loni.usc.edu/collaboration/access/appLicense.jsp#:~:text=NIFD%20is%20the%20nickname%20for%20the%20frontotemporal%20lobar,characterize%20longitudinal%20clinical%20and%20imaging%20changes%20in%20FTLD.)
  * [Parkinson’s Progression Markers Initiative (PPMI)](https://www.ppmi-info.org/access-data-specimens/download-data/)

### Private Datasets

  * XWH & SYSUH
  * Huashan & Sixth People’s Hospital
  * BRAINS-Data
  * RENJI

## 📖 Papers

### Representation Learning

  * “BrainPrompt: Multi-Level Brain Prompt Enhancement for Neurological Condition Identification”
  * “Clinical Dementia Rating Classification Using Integrated Vision and Language Information”
  * “Large Language Models Improve Alzheimer’s Disease Diagnosis Using Multi-Modality Data”
  * “Schema-Adaptive Tabular Representation Learning with LLMs for Generalizable Multimodal Clinical Reasoning”
  * “Diffusion with a Linguistic Compass: Steering the Generation of Clinically Plausible Future sMRI Representations for Early MCI Conversion Prediction”

### Clinical Reasoning

  * “Large Language Models Are Clinical Reasoners: Reasoning-Aware Diagnosis Framework with Prompt-Generated Rationales”
  * “A Vision-Language Model for Enhanced MCI Identification in Alzheimer’s Disease through Neuropsychological and Neuroimaging Data Integration”
  * “FLIQA-AD: A Fusion Model with Large Language Model for Better Diagnose and MMSE Prediction of Alzheimer’s Disease”
  * “An Explainable Diagnostic Framework for Neurodegenerative Dementias via Reinforcement-Optimized LLM Reasoning”
  * “NeuroSymAD: A Neuro-Symbolic Framework for Interpretable Alzheimer’s Disease Diagnosis”
  * “Tabular LLMs for Interpretable Few-Shot Alzheimer’s Disease Prediction with Multimodal Biomedical Data”

### Agent Orchestration

  * “ADAgent: LLM-based Agent for Alzheimer’s Disease Analysis”
  * “Medical Diagnosis with Tool-Augmented Reasoning Agents for Flexible Extensibility”
  * “A Large Language Model-Based Self-Learning and Critical Agent Framework for Multimodal Alzheimer’s Disease Diagnosis”
  * “NeuroAgent: LLM Agents for Multimodal Neuroimaging Analysis and Research”
  * “Towards a Virtual Neuroscientist: Autonomous Neuroimaging Analysis via Multi-Agent Collaboration”

## 🔍 Review Scope

This review covers studies that apply LLMs, multimodal LLMs, or LLM-based agents to neuroimaging-based AD diagnosis and related tasks, including:

  * AD, MCI, and cognitively normal classification
  * Early MCI conversion and disease progression prediction
  * Brain age estimation and dementia subtype identification
  * Multimodal imaging-clinical data fusion
  * Diagnostic explanation and clinical decision support
  * Tool-augmented and multi-agent neuroimaging analysis

## 📥 Citation

The citation information will be updated after publication.

```bibtex
Coming soon
```

## 📢 Contributing

If you find a relevant paper, dataset, benchmark, or resource that should be included, please open an issue or submit a pull request. Contributions that improve the coverage and organization of LLM-powered neuroimaging-based AD diagnosis are welcome.

## 📧 Contact

For questions, suggestions, or collaboration inquiries, please contact:

**Email:** To be added

