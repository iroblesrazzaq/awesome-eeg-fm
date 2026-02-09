# Awesome Brainwave Foundation Models 🧠⚡️

A curated list of **foundation models for brainwave signals**, particularly **EEG Foundation Models**.  
This repository compiles models for **representation learning**, **neural decoding**, **cross-dataset generalization**, and **clinical EEG**.

PRs welcome — please add **paper link + year + authors + (optional) code/project link + pretraining scale**.

---

## EEG Foundation Models (scalp EEG only)

### 2025
- **CSBrain** — *Zhou et al.* (NeurIPS 2025; arXiv:2506.23075)  
  **CSBrain: A Cross-scale Spatiotemporal Brain Foundation Model for EEG Decoding**  
  [paper](https://arxiv.org/abs/2506.23075) · [NeurIPS page](https://neurips.cc/virtual/2025/poster/117249) · [code](https://github.com/yuchen2199/CSBrain)

- **FEMBA** — *Tegon et al.* (arXiv / CoRR; arXiv:2502.06438)  
  **FEMBA: Efficient and Scalable EEG Analysis with a Bidirectional Mamba Foundation Model**  
  [paper](https://arxiv.org/abs/2502.06438)

- **LaBraM++** *(codebook/tokenizer FM)* — *Barmpas et al.* (arXiv / CoRR; arXiv:2505.16724)  
  **Advancing Brainwave Modeling with a Codebook-Based Foundation Model**  
  [paper](https://arxiv.org/abs/2505.16724)

- **LUNA** — *Döner, Ingolfsson, Benini, Li* (NeurIPS 2025; arXiv:2510.22257)  
  **LUNA: Efficient and Topology-Agnostic Foundation Model for EEG Signal Analysis**  
  Pretraining scale: **TUEG + Siena, 21,000+ hours**  
  [paper](https://arxiv.org/abs/2510.22257) · [code](https://github.com/pulp-bio/BioFoundation)

- **NeurIPT** — *Fang et al.* (NeurIPS 2025; arXiv:2510.16548)  
  **NeurIPT: Foundation Model for Neural Interfaces**  
  [paper](https://arxiv.org/abs/2510.16548) · [NeurIPS page](https://neurips.cc/virtual/2025/poster/119245)

- **REVE** — *El Ouahidi et al.* (NeurIPS 2025; arXiv:2510.21585)  
  **REVE: A Foundation Model for EEG — Adapting to Any Setup with Large-Scale Pretraining on 25,000 Subjects**  
  Pretraining scale: **92 datasets, 25,000 subjects, 60,000+ hours**  
  [paper](https://arxiv.org/abs/2510.21585) · [NeurIPS page](https://neurips.cc/virtual/2025/poster/117334) · [project](https://brain-bzh.github.io/reve/)

- **THD-BAR** — *Yang et al.* (NeurIPS 2025; arXiv:2511.13733)  
  **THD-BAR: Topology Hierarchical Derived Brain Autoregressive Modeling for EEG Generic Representations**  
  [paper](https://arxiv.org/abs/2511.13733) · [NeurIPS page](https://neurips.cc/virtual/2025/poster/119791) · [code](#)

### 2024
- **EEGFormer** — *Chen et al.* (AAAI 2024 Spring Symposium on Clinical Foundation Models; arXiv:2401.10278)  
  **EEGFormer: Towards Transferable and Interpretable Large-Scale EEG Foundation Model**  
  [paper](https://arxiv.org/abs/2401.10278)

- **LaBraM** — *Jiang et al.* (ICLR 2024 Spotlight; arXiv:2405.18765)  
  **Large Brain Model for Learning Generic Representations with Tremendous EEG Data in BCI**  
  Pretraining scale: **~2,500 hours, ~20 datasets**  
  [paper](https://arxiv.org/abs/2405.18765)

- **NeuroLM** — *Jiang et al.* (arXiv / CoRR; arXiv:2409.00101)  
  **NeuroLM: A Universal Multi-task Foundation Model for Bridging the Gap between Language and EEG Signals**  
  Pretraining scale: **~25,000 hours** (and **NeuroLM-XL: 1.7B params**)  
  [paper](https://arxiv.org/abs/2409.00101)

- **Neuro-GPT** — *Cui et al.* (arXiv / CoRR; arXiv:2311.03764)  
  **Neuro-GPT: Towards A Foundation Model for EEG**  
  [paper](https://arxiv.org/abs/2311.03764) · [code](https://github.com/wenhui0206/NeuroGPT)

### 2023
- **BIOT** — *Yang, Westover, Sun* (NeurIPS 2023; arXiv:2305.10351)  
  **BIOT: Biosignal Transformer for Cross-data Learning in the Wild**  
  [paper](https://arxiv.org/abs/2305.10351) · [NeurIPS page](https://neurips.cc/virtual/2023/poster/71117) · [code](https://github.com/ycq091044/BIOT)

### 2021
- **BENDR** — *Kostas, Aroca-Ouellette, Rudzicz* (arXiv / CoRR; arXiv:2101.12037)  
  **BENDR: Using Transformers and a Contrastive Self-Supervised Learning Task to Learn from Massive Amounts of EEG Data**  
  [paper](https://arxiv.org/abs/2101.12037)

---

## Multimodal brainwave Foundation Models (EEG + other modalities)

### 2025
- **BrainOmni** *(EEG + MEG)* — *Xiao et al.* (NeurIPS 2025; arXiv:2505.18185)  
  **BrainOmni: A Brain Foundation Model for Unified EEG and MEG Signals**  
  Pretraining scale: **1,997 hours EEG + 656 hours MEG**  
  [paper](https://arxiv.org/abs/2505.18185) · [code](https://github.com/OpenTSLab/BrainOmni)

---

## Non-EEG brainwave Foundation Models (intracranial / other modalities)

### 2023
- **BrainBERT** *(iEEG)* — *Wang et al.* (ICLR 2023; arXiv:2302.14367)  
  **BrainBERT: Self-supervised Representation Learning for Intracranial Recordings**  
  [paper](https://arxiv.org/abs/2302.14367)

---

## Benchmarks
- **AdaBrain-Bench** (Wei et al., 2024) — https://github.com/Jamine-W/AdaBrain-Bench  
- **EEG-FM-Bench** (Xiong et al., 2025) — https://github.com/xw1216/EEG-FM-Bench  
- **EEG-Bench** (Kastrati et al., 2025) — https://github.com/ETH-DISCO/EEG-Bench  

---

## Datasets & Repositories
- **TUH EEG Corpus** — https://www.isip.piconepress.com/projects/tuh_eeg/  
- **PhysioNet** — https://physionet.org/  
- **OpenNeuro** — https://openneuro.org/  
- **DANDI Archive** — https://dandiarchive.org/  

---

## Contributing
Open an issue or PR with:
- model name
- year
- authors
- paper link
- code/project link (if available)
- (optional) pretraining scale: subjects / hours / channel-hours
