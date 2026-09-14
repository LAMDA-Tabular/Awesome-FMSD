# Awesome-FMSD

A curated, continuously maintained list of foundation models for structured data (FMSD) and agentic workflows.

Our survey: **From Universal Prediction to Universal Workflows: A Survey of Foundation Models for Tabular and Time Series Data**. [Read the paper (link coming soon)](PAPER_URL_PLACEHOLDER).

This list primarily covers foundation models and foundation-model-based prediction methods for tabular and time series data, alongside agents and their workflow components. Graph and relational foundation models are maintained in a separate extension section. Standalone benchmarks, other surveys, and conventional task-specific models are outside the scope of this list.

Papers are listed by year within each category. Multi-task models appear in both time-series categories when they support forecasting and classification. Venue entries distinguish main conferences, workshops, journals, and other releases; CoRR denotes an arXiv preprint, not a peer-reviewed venue. A dash indicates an unconfirmed venue, method name, or public GitHub repository.

## Contents

- [Tabular Foundation Model](#tabular-foundation-model)
- [Time Series Forecasting Foundation Model](#time-series-forecasting-foundation-model)
- [Time Series Classification Foundation Model](#time-series-classification-foundation-model)
- [Agentic Workflow](#agentic-workflow)
- [Graph / Relational Extension](#graph--relational-extension)
- [Citation](#citation)

## Tabular Foundation Model

| Paper Title | Method | Year | Venue | Paper | GitHub |
| --- | --- | --- | --- | --- | --- |
| EXAONE Tabular 1.0: Technical Report | EXAONE Tabular | 2026 | CoRR | [Paper](https://arxiv.org/abs/2608.25774) | [GitHub](https://github.com/LGAI-Research/EXAONE-Tabular) |
| Introducing TabFM: A Zero-Shot Foundation Model for Tabular Data | TabFM | 2026 | Google Research Blog | [Paper](https://research.google/blog/introducing-tabfm-a-zero-shot-foundation-model-for-tabular-data/) | [GitHub](https://github.com/google-research/tabfm) |
| Mitra-v2 Technical Report | Mitra-v2 | 2026 | CoRR | [Paper](https://arxiv.org/abs/2609.04540) | - |
| MultiModalPFN: Extending Prior-Data Fitted Networks for Multimodal Tabular Learning | MultiModalPFN / MMPFN | 2026 | CVPR | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Kim_MultiModalPFN_Extending_Prior-Data_Fitted_Networks_for_Multimodal_Tabular_Learning_CVPR_2026_paper.html) | [GitHub](https://github.com/too-z/MultiModalPFN) |
| Synthefy Nori: Tabular Foundation Model for Regression | Nori | 2026 | Zenodo (software) | [Record](https://doi.org/10.5281/zenodo.20710462) | [GitHub](https://github.com/Synthefy/synthefy-nori) |
| TabICLv2: A better, faster, scalable, and open tabular foundation model | TabICLv2 | 2026 | CoRR | [Paper](https://arxiv.org/abs/2602.11139) | [GitHub](https://github.com/soda-inria/tabicl) |
| TabPFN-3: Technical Report | TabPFN-3 | 2026 | CoRR | [Paper](https://arxiv.org/abs/2605.13986) | [GitHub](https://github.com/PriorLabs/tabpfn-client) |
| TabSwift: An Efficient Tabular Foundation Model with Row-Wise Attention | TabSwift | 2026 | ICML | [Paper](https://arxiv.org/abs/2606.07345) | [GitHub](https://github.com/LAMDA-Tabular/TabSwift) |
| Xiaomi-TabLDM: A Tabular Foundation Model Technical Report | Xiaomi-TabLDM | 2026 | CoRR | [Paper](https://arxiv.org/abs/2609.03880) | [GitHub](https://github.com/xiaomi-research/xiaomi-tabldm) |
| Accurate predictions on small data with a tabular foundation model | TabPFN v2 | 2025 | Nature | [Paper](https://www.nature.com/articles/s41586-024-08328-6) | [GitHub](https://github.com/PriorLabs/TabPFN) |
| Attic: A New Architecture for Tabular In-Context Learning Transformers | Attic | 2025 | OpenReview | [Paper](https://openreview.net/forum?id=DSl9sSuUhp) | - |
| ConTextTab: A Semantics-Aware Tabular In-Context Learner | ConTextTab | 2025 | NeurIPS | [Paper](https://proceedings.neurips.cc/paper_files/paper/2025/hash/d807e7678ba3afd3a904f4af52819e77-Abstract-Conference.html) | [GitHub](https://github.com/SAP-samples/sap-rpt-1-oss) |
| EquiTabPFN: A Target-Permutation Equivariant Prior Fitted Network | EquiTabPFN | 2025 | NeurIPS | [Paper](https://proceedings.neurips.cc/paper_files/paper/2025/hash/5a66c7adffdbde9dd5e78820cbf6935c-Abstract-Conference.html) | [GitHub](https://github.com/MichaelArbel/EquiTabPFN) |
| Fine-tuned In-Context Learning Transformers are Excellent Tabular Data Classifiers | TabForestPFN | 2025 | CoRR | [Paper](https://arxiv.org/abs/2405.13396) | - |
| iLTM: Integrated Large Tabular Model | iLTM | 2025 | CoRR | [Paper](https://arxiv.org/abs/2511.15941) | [GitHub](https://github.com/AI-sandbox/iLTM) |
| LimiX: Unleashing Structured-Data Modeling Capability for Generalist Intelligence | LimiX | 2025 | CoRR | [Paper](https://arxiv.org/abs/2509.03505) | [GitHub](https://github.com/limix-ldm-ai/LimiX) |
| MachineLearningLM: Scaling Many-shot In-context Learning via Continued Pretraining | MachineLearningLM | 2025 | CoRR | [Paper](https://arxiv.org/abs/2509.06806) | [GitHub](https://github.com/HaoAreYuDong/MachineLearningLM) |
| Mitra: Mixed Synthetic Priors for Enhancing Tabular Foundation Models | Mitra | 2025 | NeurIPS | [Paper](https://proceedings.neurips.cc/paper_files/paper/2025/hash/177d68f4adef163b7b123b5c5adb3c60-Abstract-Conference.html) | - |
| MotherNet: Fast Training and Inference via Hyper-Network Transformers | MotherNet | 2025 | ICLR | [Paper](https://proceedings.iclr.cc/paper_files/paper/2025/hash/bed8e95c6a99df485a6fc8b973e2d6cb-Abstract-Conference.html) | [GitHub](https://github.com/microsoft/ticl) |
| Orion-MSP: Multi-Scale Sparse Attention for Tabular In-Context Learning | Orion-MSP | 2025 | CoRR | [Paper](https://arxiv.org/abs/2511.02818) | [GitHub](https://github.com/Lexsi-Labs/Orion-MSP) |
| State-Space Models for Tabular Prior-Data Fitted Networks | Hydra | 2025 | ICML FMSD Workshop | [Paper](https://arxiv.org/abs/2510.14573) | [GitHub](https://github.com/felixmkoch/Structured-State-Space-Models-for-PFNs) |
| TabDPT: Scaling Tabular Foundation Models on Real Data | TabDPT | 2025 | NeurIPS | [Paper](https://proceedings.neurips.cc/paper_files/paper/2025/hash/fc0e3f908a2116ba529ad0a1530a3675-Abstract-Conference.html) | [GitHub](https://github.com/layer6ai-labs/TabDPT-inference) |
| TabICL: A Tabular Foundation Model for In-Context Learning on Large Data | TabICL | 2025 | ICML | [Paper](https://proceedings.mlr.press/v267/qu25d.html) | [GitHub](https://github.com/soda-inria/tabicl) |
| TabPFN-2.5: Advancing the State of the Art in Tabular Foundation Models | TabPFN v2.5 | 2025 | CoRR | [Paper](https://arxiv.org/abs/2511.08667) | [GitHub](https://github.com/PriorLabs/tabpfn-client) |
| Zero-shot Meta-learning for Tabular Prediction Tasks with Adversarially Pre-trained Transformer | APT | 2025 | ICML | [Paper](https://proceedings.mlr.press/v267/wu25c.html) | [GitHub](https://github.com/yulun-rayn/APT) |
| CARTE: Pretraining and Transfer for Tabular Learning | CARTE | 2024 | ICML | [Paper](https://proceedings.mlr.press/v235/kim24d.html) | [GitHub](https://github.com/soda-inria/carte) |
| Cross-Table Pretraining towards a Universal Function Space for Heterogeneous Tabular Data | XTFormer | 2024 | CoRR | [Paper](https://arxiv.org/abs/2406.00281) | - |
| From Supervised to Generative: A Novel Paradigm for Tabular Deep Learning with Large Language Models | GTL | 2024 | SIGKDD | [Paper](https://doi.org/10.1145/3637528.3671975) | - |
| HyperFast: Instant Classification for Tabular Data | HyperFast | 2024 | AAAI | [Paper](https://doi.org/10.1609/aaai.v38i10.28988) | [GitHub](https://github.com/AI-sandbox/HyperFast) |
| Large Scale Transfer Learning for Tabular Data via Language Modeling | RTFM / TabuLa-8B | 2024 | NeurIPS | [Paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/4fd5cfd2e31bebbccfa5ffa354c04bdc-Abstract-Conference.html) | [GitHub](https://github.com/mlfoundations/rtfm) |
| Making Pre-trained Language Models Great on Tabular Prediction | TP-BERTa | 2024 | ICLR | [Paper](https://proceedings.iclr.cc/paper_files/paper/2024/hash/668563ef18fbfef0b66af491ea334d5f-Abstract-Conference.html) | [GitHub](https://github.com/jyansir/tp-berta) |
| MediTab: Scaling Medical Tabular Data Predictors via Data Consolidation, Enrichment, and Refinement | MediTab | 2024 | IJCAI | [Paper](https://www.ijcai.org/proceedings/2024/0670) | - |
| Towards Cross-Table Masked Pretraining for Web Data Mining | CM2 | 2024 | WWW | [Paper](https://doi.org/10.1145/3589334.3645707) | - |
| UniTabE: A Universal Pretraining Protocol for Tabular Foundation Model in Data Science | UniTabE | 2024 | ICLR | [Paper](https://proceedings.iclr.cc/paper_files/paper/2024/hash/765c6e0249a301664092b16a39643f88-Abstract-Conference.html) | - |
| Rethinking Pre-Training in Tabular Data: A Neighborhood Embedding Perspective | TabPTM | 2023 | CoRR | [Paper](https://arxiv.org/abs/2311.00055) | - |
| TabLLM: Few-shot Classification of Tabular Data with Large Language Models | TabLLM | 2023 | AISTATS | [Paper](https://proceedings.mlr.press/v206/hegselmann23a.html) | [GitHub](https://github.com/clinicalml/TabLLM) |
| TabPFN: A Transformer That Solves Small Tabular Classification Problems in a Second | TabPFN | 2023 | ICLR | [Paper](https://openreview.net/forum?id=cp5PvcI6w8_) | [GitHub](https://github.com/PriorLabs/TabPFN) |
| XTab: Cross-table Pretraining for Tabular Transformers | XTab | 2023 | ICML | [Paper](https://proceedings.mlr.press/v202/zhu23k.html) | [GitHub](https://github.com/BingzhaoZhu/XTab) |
| LIFT: Language-Interfaced Fine-Tuning for Non-language Machine Learning Tasks | LIFT | 2022 | NeurIPS | [Paper](https://proceedings.neurips.cc/paper_files/paper/2022/hash/4ce7fe1d2730f53cb3857032952cd1b8-Abstract-Conference.html) | [GitHub](https://github.com/UW-Madison-Lee-Lab/LanguageInterfacedFineTuning) |
| TransTab: Learning Transferable Tabular Transformers Across Tables | TransTab | 2022 | NeurIPS | [Paper](https://proceedings.neurips.cc/paper_files/paper/2022/hash/1377f76686d56439a2bd7a91859972f5-Abstract-Conference.html) | [GitHub](https://github.com/RyanWangZf/transtab) |

## Time Series Forecasting Foundation Model

| Paper Title | Method | Year | Venue | Paper | GitHub |
| --- | --- | --- | --- | --- | --- |
| Chronicle: A Multimodal Foundation Model for Joint Language and Time Series Understanding | Chronicle | 2026 | CoRR | [Paper](https://arxiv.org/abs/2605.20268) | - |
| Timer-S1: A Billion-Scale Time Series Foundation Model with Serial Scaling | Timer-S1 | 2026 | CoRR | [Paper](https://arxiv.org/abs/2603.04791) | - |
| Chronos-2: From Univariate to Universal Forecasting | Chronos-2 | 2025 | CoRR | [Paper](https://arxiv.org/abs/2510.15821) | [GitHub](https://github.com/amazon-science/chronos-forecasting) |
| Eliciting Chain-of-Thought Reasoning for Time Series Analysis using Reinforcement Learning | COUNTS | 2025 | CoRR | [Paper](https://arxiv.org/abs/2510.01116) | - |
| From Tables to Time: Extending TabPFN-v2 to Time Series Forecasting | TabPFN-TS | 2025 | CoRR | [Paper](https://arxiv.org/abs/2501.02945) | [GitHub](https://github.com/PriorLabs/tabpfn-time-series) |
| Kairos: Toward Adaptive and Parameter-Efficient Time Series Foundation Models | Kairos | 2025 | CoRR | [Paper](https://arxiv.org/abs/2509.25826) | - |
| LLM4TS: Aligning Pre-Trained LLMs as Data-Efficient Time-Series Forecasters | LLM4TS | 2025 | ACM TIST | [Paper](https://doi.org/10.1145/3719207) | [GitHub](https://github.com/blacksnail789521/LLM4TS) |
| Moirai 2.0: When Less Is More for Time Series Forecasting | Moirai 2.0 | 2025 | CoRR | [Paper](https://arxiv.org/abs/2511.11698) | [GitHub](https://github.com/SalesforceAIResearch/uni2ts) |
| Moirai-MoE: Empowering Time Series Foundation Models with Sparse Mixture of Experts | Moirai-MoE | 2025 | ICML | [Paper](https://proceedings.mlr.press/v267/liu25an.html) | [GitHub](https://github.com/SalesforceAIResearch/uni2ts) |
| Sundial: A Family of Highly Capable Time Series Foundation Models | Sundial | 2025 | ICML | [Paper](https://proceedings.mlr.press/v267/liu25be.html) | [GitHub](https://github.com/thuml/Sundial) |
| TempoPFN: Synthetic Pre-training of Linear RNNs for Zero-shot Time Series Forecasting | TempoPFN | 2025 | CoRR | [Paper](https://arxiv.org/abs/2510.25502) | [GitHub](https://github.com/automl/TempoPFN) |
| Time Series Forecasting via Reasoning: A Slow-Thinking Approach with Reinforcement Fine-Tuned LLMs | Time-R1 | 2025 | CoRR | [Paper](https://arxiv.org/abs/2506.10630) | [GitHub](https://github.com/ustc-time-series/Time-R1) |
| Time-MoE: Billion-Scale Time Series Foundation Models with Mixture of Experts | Time-MoE | 2025 | ICLR | [Paper](https://proceedings.iclr.cc/paper_files/paper/2025/hash/558d48c1f08675daa636e09bfe94a89e-Abstract-Conference.html) | [GitHub](https://github.com/Time-MoE/Time-MoE) |
| TiRex: Zero-Shot Forecasting Across Long and Short Horizons with Enhanced In-Context Learning | TiRex | 2025 | NeurIPS | [Paper](https://proceedings.neurips.cc/paper_files/paper/2025/hash/5356603f9c47399adfd372f77a677057-Abstract-Conference.html) | [GitHub](https://github.com/NX-AI/tirex) |
| Vision-Enhanced Time Series Forecasting via Latent Diffusion Models | LDM4TS | 2025 | CoRR | [Paper](https://arxiv.org/abs/2502.14887) | - |
| VisionTS: Visual Masked Autoencoders Are Free-Lunch Zero-Shot Time Series Forecasters | VisionTS | 2025 | ICML | [Paper](https://proceedings.mlr.press/v267/chen25be.html) | [GitHub](https://github.com/Keytoyze/VisionTS) |
| A decoder-only foundation model for time-series forecasting | TimesFM | 2024 | ICML | [Paper](https://proceedings.mlr.press/v235/das24c.html) | [GitHub](https://github.com/google-research/timesfm) |
| A Mamba Foundation Model for Time Series Forecasting | TSMamba | 2024 | CoRR | [Paper](https://arxiv.org/abs/2411.02941) | - |
| Chronos: Learning the Language of Time Series | Chronos | 2024 | TMLR | [Paper](https://openreview.net/forum?id=gerNCVqqtR) | [GitHub](https://github.com/amazon-science/chronos-forecasting) |
| DAM: Towards a Foundation Model for Forecasting | DAM | 2024 | ICLR | [Paper](https://proceedings.iclr.cc/paper_files/paper/2024/hash/201e691e8a0940291dc591eb0439a789-Abstract-Conference.html) | - |
| GPT4MTS: Prompt-based Large Language Model for Multimodal Time-series Forecasting | GPT4MTS | 2024 | AAAI | [Paper](https://doi.org/10.1609/aaai.v38i21.30383) | - |
| Large Pre-trained time series models for cross-domain Time series analysis tasks | LPTM | 2024 | NeurIPS | [Paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/662dcc5c2b9aca77b2a0ec8a98aefae9-Abstract-Conference.html) | [GitHub](https://github.com/AdityaLab/LPTM) |
| MOMENT: A Family of Open Time-series Foundation Models | MOMENT | 2024 | ICML | [Paper](https://proceedings.mlr.press/v235/goswami24a.html) | [GitHub](https://github.com/moment-timeseries-foundation-model/moment) |
| Time-LLM: Time Series Forecasting by Reprogramming Large Language Models | Time-LLM | 2024 | ICLR | [Paper](https://proceedings.iclr.cc/paper_files/paper/2024/hash/680b2a8135b9c71278a09cafb605869e-Abstract-Conference.html) | [GitHub](https://github.com/KimMeen/Time-LLM) |
| TimeDiT: General-purpose Diffusion Transformers for Time Series Foundation Model | TimeDiT | 2024 | CoRR | [Paper](https://arxiv.org/abs/2409.02322) | - |
| Timer: Generative Pre-trained Transformers Are Large Time Series Models | Timer | 2024 | ICML | [Paper](https://proceedings.mlr.press/v235/liu24cb.html) | [GitHub](https://github.com/thuml/Large-Time-Series-Model) |
| Tiny Time Mixers (TTMs): Fast Pre-trained Models for Enhanced Zero/Few-Shot Forecasting of Multivariate Time Series | TTM | 2024 | NeurIPS | [Paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/874a4d89f2d04b4bcf9a2c19545cf040-Abstract-Conference.html) | [GitHub](https://github.com/ibm-granite/granite-tsfm/tree/main/tsfm_public/models/tinytimemixer) |
| TOTEM: TOkenized Time Series EMbeddings for General Time Series Analysis | TOTEM | 2024 | TMLR | [Paper](https://openreview.net/forum?id=QlTLkH6xRC) | [GitHub](https://github.com/SaberaTalukder/TOTEM) |
| Unified Training of Universal Time Series Forecasting Transformers | Moirai | 2024 | ICML | [Paper](https://proceedings.mlr.press/v235/woo24a.html) | [GitHub](https://github.com/SalesforceAIResearch/uni2ts) |
| UniTime: A Language-Empowered Unified Model for Cross-Domain Time Series Forecasting | UniTime | 2024 | WWW | [Paper](https://doi.org/10.1145/3589334.3645434) | [GitHub](https://github.com/liuxu77/UniTime) |
| UniTS: A Unified Multi-Task Time Series Model | UniTS | 2024 | NeurIPS | [Paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/fe248e22b241ae5a9adf11493c8c12bc-Abstract-Conference.html) | [GitHub](https://github.com/mims-harvard/UniTS) |
| ForecastPFN: Synthetically-Trained Zero-Shot Forecasting | ForecastPFN | 2023 | NeurIPS | [Paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/0731f0e65559059eb9cd9d6f44ce2dd8-Abstract-Conference.html) | [GitHub](https://github.com/abacusai/forecastpfn) |
| Lag-Llama: Towards Foundation Models for Probabilistic Time Series Forecasting | Lag-Llama | 2023 | CoRR | [Paper](https://arxiv.org/abs/2310.08278) | [GitHub](https://github.com/time-series-foundation-models/lag-llama) |
| Large Language Models Are Zero-Shot Time Series Forecasters | LLMTime | 2023 | NeurIPS | [Paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/3eb7ca52e8207697361b2c0fb3926511-Abstract-Conference.html) | [GitHub](https://github.com/ngruver/llmtime) |
| One Fits All: Power General Time Series Analysis by Pretrained LM | GPT4TS | 2023 | NeurIPS | [Paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/86c17de05579cde52025f9984e6e2ebb-Abstract-Conference.html) | [GitHub](https://github.com/DAMO-DI-ML/NeurIPS2023-One-Fits-All) |
| TimeGPT-1 | TimeGPT | 2023 | CoRR | [Paper](https://arxiv.org/abs/2310.03589) | - |

## Time Series Classification Foundation Model

| Paper Title | Method | Year | Venue | Paper | GitHub |
| --- | --- | --- | --- | --- | --- |
| A Unified Shape-Aware Foundation Model for Time Series Classification | UniShape | 2026 | AAAI | [Paper](https://doi.org/10.1609/aaai.v40i28.39574) | - |
| CauKer: Classification Time Series Foundation Models Can Be Pretrained on Synthetic Data | CauKer | 2026 | ICLR | [Paper](https://proceedings.iclr.cc/paper_files/paper/2026/hash/702b67152ec4435795f681865b67999c-Abstract-Conference.html) | - |
| Chronicle: A Multimodal Foundation Model for Joint Language and Time Series Understanding | Chronicle | 2026 | CoRR | [Paper](https://arxiv.org/abs/2605.20268) | - |
| MantisV2: Closing the Zero-Shot Gap in Time Series Classification with Synthetic Data and Test-Time Strategies | MantisV2 | 2026 | CoRR | [Paper](https://arxiv.org/abs/2602.17868) | [GitHub](https://github.com/vfeofanov/mantis) |
| Rethinking Zero-Shot Time Series Classification: From Task-specific Classifiers to In-Context Inference | TIC-FM | 2026 | CoRR | [Paper](https://arxiv.org/abs/2602.00620) | [GitHub](https://github.com/fangjuntao/TIC-FM) |
| TimEE: Towards End-to-end Time Series Classification via In-Context Learning | TimEE | 2026 | ICLR TSALM Workshop | [Paper](https://openreview.net/forum?id=heYrOmVFtY) | [GitHub](https://github.com/automl/timee) |
| Eliciting Chain-of-Thought Reasoning for Time Series Analysis using Reinforcement Learning | COUNTS | 2025 | CoRR | [Paper](https://arxiv.org/abs/2510.01116) | - |
| Mantis: Lightweight Foundation Model for Time Series Classification | Mantis | 2025 | CoRR | [Paper](https://arxiv.org/abs/2502.15637) | [GitHub](https://github.com/vfeofanov/mantis) |
| TiCT: A Synthetically Pre-Trained Foundation Model for Time Series Classification | TiCT | 2025 | CoRR | [Paper](https://arxiv.org/abs/2511.19694) | - |
| Time Series Representations for Classification Lie Hidden in Pretrained Vision Transformers | TiViT | 2025 | CoRR | [Paper](https://arxiv.org/abs/2506.08641) | [GitHub](https://github.com/ExplainableML/TiViT) |
| Large Pre-trained time series models for cross-domain Time series analysis tasks | LPTM | 2024 | NeurIPS | [Paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/662dcc5c2b9aca77b2a0ec8a98aefae9-Abstract-Conference.html) | [GitHub](https://github.com/AdityaLab/LPTM) |
| MOMENT: A Family of Open Time-series Foundation Models | MOMENT | 2024 | ICML | [Paper](https://proceedings.mlr.press/v235/goswami24a.html) | [GitHub](https://github.com/moment-timeseries-foundation-model/moment) |
| UniTS: A Unified Multi-Task Time Series Model | UniTS | 2024 | NeurIPS | [Paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/fe248e22b241ae5a9adf11493c8c12bc-Abstract-Conference.html) | [GitHub](https://github.com/mims-harvard/UniTS) |
| One Fits All: Power General Time Series Analysis by Pretrained LM | GPT4TS | 2023 | NeurIPS | [Paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/86c17de05579cde52025f9984e6e2ebb-Abstract-Conference.html) | [GitHub](https://github.com/DAMO-DI-ML/NeurIPS2023-One-Fits-All) |

## Agentic Workflow

| Paper Title | Method | Year | Venue | Paper | GitHub |
| --- | --- | --- | --- | --- | --- |
| Agentic Data Intelligence for General Tabular Modeling | TabAgent | 2026 | ICML FMSD Workshop | [Paper](https://openreview.net/forum?id=pj1XShgzSv) | - |
| LLM-FE: Automated Feature Engineering for Tabular Data with LLMs as Evolutionary Optimizers | LLM-FE | 2026 | TMLR | [Paper](https://openreview.net/forum?id=qvI35hkpOO) | [GitHub](https://github.com/nikhilsab/LLMFE) |
| MATA: Multi-Agent Framework for Reliable and Flexible Table Question Answering | MATA | 2026 | ACL Findings | [Paper](https://aclanthology.org/2026.findings-acl.1672/) | [GitHub](https://github.com/AIDASLab/MATA) |
| TableMaster: A Recipe to Advance Table Understanding with Language Models | TableMaster | 2026 | ICLR | [Paper](https://proceedings.iclr.cc/paper_files/paper/2026/hash/f59744fb1961b33c3b3a0fb18b1fa723-Abstract-Conference.html) | - |
| TableMind++: An Uncertainty-Aware Programmatic Agent for Tool-Augmented Table Reasoning | TableMind++ | 2026 | CoRR | [Paper](https://arxiv.org/abs/2603.07528) | [GitHub](https://github.com/fishsure/TableMind-PP) |
| TableMind: An Autonomous Programmatic Agent for Tool-Augmented Table Reasoning | TableMind | 2026 | WSDM | [Paper](https://doi.org/10.1145/3773966.3777932) | - |
| TabTracer: Monte Carlo Tree Search for Complex Table Reasoning with Large Language Models | TabTracer | 2026 | CoRR | [Paper](https://arxiv.org/abs/2602.14089) | - |
| TimeSage-MT: A Multi-Turn Benchmark for Evaluating Agentic Time Series Reasoning | TimeSage | 2026 | CoRR | [Paper](https://arxiv.org/abs/2606.01498) | [GitHub](https://github.com/TimeSage-Series/TimeSage-MT) |
| TSRouter: Dynamic Modality-Model Selection for Time Series Reasoning | TSRouter | 2026 | CoRR | [Paper](https://arxiv.org/abs/2607.08940) | [GitHub](https://github.com/tianyi-lab/TSRouter) |
| AgentHPO: Large Language Model Agent for Hyper-Parameter Optimization | AgentHPO | 2025 | CPAL | [Paper](https://proceedings.mlr.press/v280/liu25c.html) | - |
| AIDE: AI-Driven Exploration in the Space of Code | AIDE | 2025 | CoRR | [Paper](https://arxiv.org/abs/2502.13138) | [GitHub](https://github.com/WecoAI/aideml) |
| Cleaning Maintenance Logs with LLM Agents for Improved Predictive Maintenance | - | 2025 | CoRR | [Paper](https://arxiv.org/abs/2511.05311) | [GitHub](https://github.com/sntubix/agentic-pdm-log-cleaning) |
| Exploring LLM Agents for Cleaning Tabular Machine Learning Datasets | - | 2025 | CoRR | [Paper](https://arxiv.org/abs/2503.06664) | - |
| FeRG-LLM : Feature Engineering by Reason Generation Large Language Models | FeRG-LLM | 2025 | NAACL Findings | [Paper](https://aclanthology.org/2025.findings-naacl.237/) | - |
| LLM Meeting Decision Trees on Tabular Data | DeLTa | 2025 | NeurIPS | [Paper](https://proceedings.neurips.cc/paper_files/paper/2025/hash/ab3b2b8d2bb4a1be648a91d150a3b87a-Abstract-Conference.html) | [GitHub](https://github.com/HangtingYe/DeLTa) |
| Make Still Further Progress: Chain of Thoughts for Tabular Data Leaderboard | CoT2 | 2025 | ICML FMSD Workshop | [Paper](https://arxiv.org/abs/2505.13421) | - |
| ML-Master: Towards AI-for-AI via Integration of Exploration and Reasoning | ML-Master | 2025 | CoRR | [Paper](https://arxiv.org/abs/2506.16499) | - |
| MLZero: A Multi-Agent System for End-to-end Machine Learning Automation | MLZero | 2025 | CoRR | [Paper](https://arxiv.org/abs/2505.13941) | [GitHub](https://github.com/autogluon/autogluon-assistant) |
| Synergizing Large Language Models and Knowledge-Based Reasoning for Interpretable Feature Engineering | ReaGen | 2025 | WWW | [Paper](https://doi.org/10.1145/3696410.3714720) | - |
| Tabular Feature Discovery With Reasoning Type Exploration | ReFeat | 2025 | CoRR | [Paper](https://arxiv.org/abs/2506.20357) | - |
| TALON: A Multi-Agent Framework for Long-Table Exploration and Question Answering | TALON | 2025 | EMNLP | [Paper](https://aclanthology.org/2025.emnlp-main.1393/) | [GitHub](https://github.com/Wwestmoon/TALON) |
| AutoKaggle: A Multi-Agent Framework for Autonomous Data Science Competitions | AutoKaggle | 2024 | CoRR | [Paper](https://arxiv.org/abs/2410.20424) | [GitHub](https://github.com/multimodal-art-projection/AutoKaggle) |
| CleanAgent: Automating Data Standardization with LLM-based Agents | CleanAgent | 2024 | CoRR | [Paper](https://arxiv.org/abs/2403.08291) | [GitHub](https://github.com/sfu-db/CleanAgent) |
| Large Language Models Can Automatically Engineer Features for Few-Shot Tabular Learning | FeatLLM | 2024 | ICML | [Paper](https://proceedings.mlr.press/v235/han24f.html) | [GitHub](https://github.com/Sungwon-Han/FeatLLM) |
| Optimized Feature Generation for Tabular Data via LLMs with Decision Tree Reasoning | OCTree | 2024 | NeurIPS | [Paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/a7ebe2e8d8cfd2fcec6cd77f9e6fd34d-Abstract-Conference.html) | [GitHub](https://github.com/jaehyun513/OCTree) |
| AutoML-GPT: Automatic Machine Learning with GPT | AutoML-GPT | 2023 | CoRR | [Paper](https://arxiv.org/abs/2305.02499) | - |
| JarviX: A LLM No code Platform for Tabular Data Analysis and Optimization | JarviX | 2023 | EMNLP (Industry Track) | [Paper](https://aclanthology.org/2023.emnlp-industry.59/) | - |
| Large Language Models for Automated Data Science: Introducing CAAFE for Context-Aware Automated Feature Engineering | CAAFE | 2023 | NeurIPS | [Paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/8c2df4c35cdbee764ebb9e9d0acd5197-Abstract-Conference.html) | [GitHub](https://github.com/noahho/CAAFE) |

## Graph / Relational Extension

This section collects the graph and relational extensions discussed in the survey, including native foundation models and methods that adapt tabular foundation models to these domains. GitHub links may provide evaluation or API examples rather than open model weights or training code.

### Graph Foundation Model

| Paper Title | Method | Year | Venue | Paper | GitHub |
| --- | --- | --- | --- | --- | --- |
| GraphPFN: A Prior-Data Fitted Graph Foundation Model | GraphPFN | 2026 | ICML | [Paper](https://arxiv.org/abs/2509.21489) | [GitHub](https://github.com/yandex-research/graphpfn) |
| Turning Tabular Foundation Models into Graph Foundation Models | G2T-FM | 2025 | NeurIPS New Perspectives in Graph Machine Learning Workshop | [Paper](https://arxiv.org/abs/2508.20906) | [GitHub](https://github.com/yandex-research/G2T-FM) |

### Relational Foundation Model

| Paper Title | Method | Year | Venue | Paper | GitHub |
| --- | --- | --- | --- | --- | --- |
| Advancing Open and Reproducible Relational Learning: RelArena-α, TabPFN-Rel and RPI | TabPFN-Rel | 2026 | CoRR | [Paper](https://arxiv.org/abs/2608.16319) | [GitHub](https://github.com/PriorLabs/relarena) |
| KumoRFM-2: Scaling Foundation Models for Relational Learning | KumoRFM-2 | 2026 | CoRR | [Paper](https://arxiv.org/abs/2604.12596) | [GitHub](https://github.com/kumo-ai/kumo-rfm) |
| Relational Transformer: Toward Zero-Shot Foundation Models for Relational Data | Relational Transformer / RT | 2026 | ICLR | [Paper](https://proceedings.iclr.cc/paper_files/paper/2026/hash/7107d4d2e837bde2171c6b71b5bde954-Abstract-Conference.html) | [GitHub](https://github.com/stanford-star/relational-transformer) |
| Griffin: Towards a Graph-Centric Relational Database Foundation Model | Griffin | 2025 | ICML | [Paper](https://proceedings.mlr.press/v267/wang25da.html) | [GitHub](https://github.com/yanxwb/Griffin) |

## Citation

Please consider citing our survey if you find this collection useful.

```bibtex
% TODO: Add the survey's BibTeX citation once publication details are available.
```
