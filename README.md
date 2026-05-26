# Awesome-ai4sci-papers

一个精选的 **AI for Science** 领域文献清单，持续更新中。

---

## Foundation Models

基于大规模生物组学数据预训练的基础模型。

| Year / Venue | Paper | Tags |
|---|---|---|
| 2024 *Nature Methods* | **scGPT: Toward Building a Foundation Model for Single-Cell Multi-Omics Using Generative AI** [[paper]](https://www.nature.com/articles/s41592-024-02161-5) [[GitHub]](https://github.com/bowang-lab/scGPT) | `Single-cell omics`, `Multi-omics` |
---

## AI Agents

具备自主规划、工具调用与反思迭代能力的 LLM 智能体，完成生物数据分析任务。

| Year / Venue | Paper | Tags |
|---|---|---|
| 2026 *Nature* | **Accelerating Scientific Discovery with Co-Scientist** [[paper]](https://doi.org/10.1038/s41586-026-10644-y) | `Cross-Modal`, `Scientific Discovery` |
| 2026 *Nature* | **An AI System to Help Scientists Write Expert-Level Empirical Software (ERA)** [[paper]](https://doi.org/10.1038/s41586-026-10658-6) | `Tools & Infrastructure`, `Pipeline Optimization` |
| 2026 *Nature* | **A Multi-Agent System for Automating Scientific Discovery (Robin)** [[paper]](https://doi.org/10.1038/s41586-026-10652-y) | `Cross-Modal`, `Scientific Discovery` |
| 2026 *Nature Methods* | **CellVoyager: AI CompBio Agent Generates New Insights by Autonomously Analyzing Biological Data** [[paper]](https://www.nature.com/articles/s41592-026-00001-0) | `Single-cell omics`, `Scientific Discovery` |
| 2026 *arxiv* | **CELLAGENT: LLM-Driven Multi-Agent Framework for Natural Language-Based Single-Cell Analysis** [[paper]](https://arxiv.org/abs/2407.09811) [[GitHub]](https://github.com/23AIBox/cellagent) | `Single-cell omics`, `Pipeline Optimization` |
| 2025 *Nature Communications* | **CASSIA: A Multi-Agent Large Language Model for Automated and Interpretable Cell Annotation** [[paper]](https://www.nature.com/articles/s41467-024-55000-6) | `Single-cell omics`, `Pipeline Optimization` |
| 2024 *Nature Methods* | **Omega: Harnessing the Power of Large Language Models for Bioimage Analysis** [[paper]](https://www.nature.com/articles/s41592-024-02310-w) | `Bioimage`, `Single-cell omics` |
| 2024 *Nature Methods* | **BioImage.IO Chatbot: A Community-Driven AI Assistant for Integrative Computational Bioimaging** [[paper]](https://www.nature.com/articles/s41592-024-02287-6) | `Bioimage` |

---

## Benchmarks

该领域的系统性综述与基准评测研究。

| Year / Venue | Paper | Tags |
|---|---|---|
| 2022 *Nature Methods* | **Benchmarking Atlas-Level Data Integration in Single-Cell Genomics** [[paper]](https://doi.org/10.1038/s41592-021-01336-8) | `Single-cell omics` |

---

## Tools & Infrastructure

广泛使用的生物信息学工具与计算基础设施。

| Year / Venue | Paper | Tags |
|---|---|---|
| 2018 *Genome Biology* | **SCANPY: Large-Scale Single-Cell Gene Expression Data Analysis** [[paper]](https://doi.org/10.1186/s13059-017-1382-0) [[GitHub]](https://github.com/theislab/scanpy) | `Single-cell omics`, `Tools & Infrastructure` |

---

## Tags 说明

| Tag | Description |
|---|---|
| `Single-cell omics` | 应用于单细胞组学数据分析，包括 scRNA-seq、scATAC-seq、scMulti-omics 等 |
| `Spatial omics` | 应用于空间组学数据分析，包括空间转录组、空间蛋白质组等 |
| `Multi-omics` | 模型设计整合了多种组学层次（如转录组 + 蛋白组 + 表观组） |
| `Bioimage` | 应用于生物医学图像分析，包括细胞图像、显微图像等 |
| `Cross-Modal` | Agent 能力跨越多个模态或领域，非单一组学任务 |
| `Scientific Discovery` | 核心能力为自主提出科学假设、设计实验方案、推动生物学新发现 |
| `Pipeline Optimization` | 核心能力为自主构建、优化、执行端到端生物信息学分析流程 |
| `Tools & Infrastructure` | 经典生物信息学工具或计算基础设施，具有广泛的应用价值 |

