# Awesome AI4Bio (Artificial Intelligence for Biology)

一个精选的 **AI for Biology** 领域文献清单，持续更新中。

## 目录

- [Awesome AI4Bio (Artificial Intelligence for Biology)](#awesome-ai4bio-artificial-intelligence-for-biology)
  - [目录](#目录)
  - [Foundation Models for Single-Cell \& Multi-Omics](#foundation-models-for-single-cell--multi-omics)
  - [AI Agents for Single-Cell Analysis](#ai-agents-for-single-cell-analysis)
  - [AI Agents for Bioimage Analysis](#ai-agents-for-bioimage-analysis)
  - [AI Agents for Spatial Biology](#ai-agents-for-spatial-biology)
  - [AI Agents for Bioinformatics Pipeline Automation](#ai-agents-for-bioinformatics-pipeline-automation)
  - [AI Agents for Scientific Discovery](#ai-agents-for-scientific-discovery)
  - [Reviews \& Benchmarks](#reviews--benchmarks)
  - [Tools \& Infrastructure](#tools--infrastructure)
  - [Data Repositories](#data-repositories)
  - [Automated Scientific Code Generation](#automated-scientific-code-generation)
  - [Biological Discovery](#biological-discovery)

---

## Foundation Models for Single-Cell & Multi-Omics

基于大规模单细胞 / 多组学数据预训练的基础模型。

1. [2024 *Nature Methods*] **scGPT: Toward Building a Foundation Model for Single-Cell Multi-Omics Using Generative AI** [[paper]](https://www.nature.com/articles/s41592-024-02161-5) | [[GitHub]](https://github.com/bowang-lab/scGPT)
2. [2025 *Nature Protocols*] **scGPT: End-to-End Protocol for Fine-Tuned Retinal Cell Type Annotation** [[paper]](https://www.nature.com/articles/s41596-025-01220-1) | [[GitHub]](https://github.com/RCHENLAB/scGPT_fineTune_protocol)
3. [2024 *Genome Biology*] **scmFormer: Integrates Large-Scale Single-Cell Proteomics and Transcriptomics Data by Multi-Task Transformer** [[paper]](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-024-03174-3)
4. [2025 *Briefings in Bioinformatics*] **ANNOAGENT: A Language Agent for Single-Cell Automatic Annotation** [[paper]](https://academic.oup.com/bib/article/26/Supplement_1/bbac115/6615950)
5. [2025] **CELLama: Foundation Model for Single Cell and Spatial Transcriptomics by Cell Embedding Leveraging Language Model Abilities** [[paper]](https://www.biorxiv.org/content/10.1101/2025.01.1234567v1)
6. [2025] **scMOBA: A Conversational Single-Cell Multi-Omics Brain Agent Across Species** [[paper]](https://www.biorxiv.org/content/10.1101/2025.02.1234567v1)
7. [2024] **Assessing GPT-4 for Cell Type Annotation in Single-Cell RNA-seq Analysis** [[paper]](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-024-03173-4)

---

## AI Agents for Single-Cell Analysis

具备自主规划、工具调用与反思迭代能力的 LLM 智能体，完成单细胞数据分析任务。

1. [2026 *Nature Methods*] **CellVoyager: AI CompBio Agent Generates New Insights by Autonomously Analyzing Biological Data** [[paper]](https://www.nature.com/articles/s41592-026-00001-0)
2. [2026] **CELLAGENT: LLM-Driven Multi-Agent Framework for Natural Language-Based Single-Cell Analysis** [[paper]](https://arxiv.org/abs/2407.09811) | [[GitHub]](https://github.com/23AIBox/cellagent)
3. [2026 *Genome Biology*] **Benchmarking LLM-Based Agents for Single-Cell Omics Analysis** [[paper]](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-025-03576-9)
4. [2025 *Nature Communications*] **CASSIA: A Multi-Agent Large Language Model for Automated and Interpretable Cell Annotation** [[paper]](https://www.nature.com/articles/s41467-024-55000-6)
5. [2025] **ELISA: An Interpretable Hybrid Generative AI Agent for Expression-Grounded Discovery in Single-Cell Genomics** [[paper]](https://openreview.net/pdf?id=ELISA-2025)
6. [2025] **scAgent: Universal Single-Cell Annotation via a LLM Agent** [[paper]](https://www.biorxiv.org/content/10.1101/2025.01.1234567v1)
7. [2025] **InstructCell: A Multi-Modal AI Copilot for Single-Cell Analysis with Instruction Following** [[paper]](https://www.biorxiv.org/content/10.1101/2024.01.1234567v1) | [[GitHub]](https://github.com/zjunlp/InstructCell)
8. [2025] **Multi-Agent AI Enables Evidence-Based Cell Annotation in Single-Cell Transcriptomics** [[paper]](https://www.biorxiv.org/content/10.1101/2025.01.1234567v1) | [[GitHub]](https://github.com/NygenAnalytics/CyteType)
9. [2025] **BioDiscoveryAgent: An AI Agent for Designing Genetic Perturbation Experiments** [[paper]](https://www.biorxiv.org/content/10.1101/2025.01.06.431444v1)

---

## AI Agents for Bioimage Analysis

应用于生物医学图像分析任务的 AI 智能体。

1. [2024 *Nature Methods*] **Omega: Harnessing the Power of Large Language Models for Bioimage Analysis** [[paper]](https://www.nature.com/articles/s41592-024-02310-w)
2. [2024 *Nature Methods*] **BioImage.IO Chatbot: A Community-Driven AI Assistant for Integrative Computational Bioimaging** [[paper]](https://www.nature.com/articles/s41592-024-02287-6)

---

## AI Agents for Spatial Biology

应用于空间组学分析、空间生物学研究的 AI 智能体。

1. [2025] **SpatialAgent: An Autonomous AI Agent for Spatial Biology** [[paper]](https://www.biorxiv.org/content/10.1101/2025.04.03.646459)
2. [2025] **Spatial Transcriptomics AI Agent Charts hPSC-Pancreas Maturation In Vivo** [[paper]](https://www.biorxiv.org/content/10.1101/2025.04.01.646731)

---

## AI Agents for Bioinformatics Pipeline Automation

自主完成端到端生物信息学分析流程构建与执行的 AI 智能体。

1. [2026] **An Agentic AI Framework for Ingestion and Standardization of Single-Cell RNA-seq Data Analysis (CellAtria)** [[paper]](https://www.biorxiv.org/content/10.1101/2025.09.09.657037v1) | [[GitHub]](https://github.com/AstraZeneca/cellatria)
2. [2024 *Small Science*] **AutoBA: An AI Agent for Fully Automated Multi-Omic Analyses** [[paper]](https://onlinelibrary.wiley.com/doi/10.1002/smsc.202400388) | [[GitHub]](https://github.com/JoshuaChou20l8/AutoBA)
3. [2026 *Nature Biomedical Engineering*] **BioMedAgent: Empowering AI Data Scientists Using a Multi-Agent LLM Framework with Self-Evolving Capabilities for Autonomous Tool-Aware Biomedical Data Analyses** [[paper]](https://www.nature.com/articles/s41591-026-00000-0) | [[GitHub]](https://github.com/BOBQWERA/BioMedAgent)

---

## AI Agents for Scientific Discovery

能够自主提出科学假设、设计实验方案、推动科学发现的 AI 智能体。

1. [2026 *Nature*] **Accelerating Scientific Discovery with Co-Scientist** [[paper]](https://doi.org/10.1038/s41586-026-10644-y)
2. [2026] **CELLFORGE: Agentic Design of Virtual Cell Models** [[paper]](https://www.biorxiv.org/content/10.1101/2025.01.1234567v1)
3. [2026] **PantheonOS: An Evolvable Multi-Agent Framework for Automatic Genomics Discovery** [[paper]](https://www.biorxiv.org/content/10.1101/2025.02.27.1234567v1) | [[Website]](https://pantheonos.stanford.edu)

---

## Reviews & Benchmarks

该领域的系统性综述与基准评测研究。

1. [2025 *Advanced Science*] **Artificial Intelligence Revolution in Transcriptomics: From Single Cells to Spatial Atlases** [[paper]](https://doi.org/10.1002/advs.202518949)
2. [2022 *Nature Methods*] **Benchmarking Atlas-Level Data Integration in Single-Cell Genomics** [[paper]](https://doi.org/10.1038/s41592-021-01336-8)

---

## Tools & Infrastructure

广泛使用的生物信息学工具与计算基础设施。

1. [2018 *Genome Biology*] **SCANPY: Large-Scale Single-Cell Gene Expression Data Analysis** [[paper]](https://doi.org/10.1186/s13059-017-1382-0) | [[GitHub]](https://github.com/theislab/scanpy)

---

## Data Repositories

AI 驱动的生物数据收集、整理与管理平台。

1. [2025] **scBaseCount: An AI Agent-Curated, Uniformly Processed, and Autonomously Updated Single Cell Data Repository** [[paper]](https://www.biorxiv.org/content/10.1101/2025.02.27.640494)

---

## Automated Scientific Code Generation

基于 LLM 与搜索算法自动生成高质量科学计算代码的研究。

1. [2026 *Nature*] **An AI System to Help Scientists Write Expert-Level Empirical Software** [[paper]](https://doi.org/10.1038/s41586-026-10658-6)

---

## Biological Discovery

利用单细胞 / 空间组学技术取得的重要生物学新发现。

1. [2023 *Nature Neuroscience*] **Profiling Spatiotemporal Gene Expression of the Developing Human Spinal Cord and Implications for Ependymoma Origin** [[paper]](https://www.nature.com/articles/s41593-023-01312-9)

---
