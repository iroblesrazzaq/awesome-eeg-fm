# Awesome Brainwave Foundation Models 🧠⚡️

A curated list of **foundation models for brainwave signals**, particularly **EEG Foundation Models**.  
This repository compiles models for **representation learning**, **neural decoding**, **cross-dataset generalization**, and **clinical EEG**.

PRs welcome — please add **paper link + year + authors + (optional) code/project link + pretraining scale**.

---

## EEG Foundation Models (scalp EEG only)

### 2025
- **CSBrain** — *Zhou et al.*  
  [paper](#) · [code](https://github.com/yuchen2199/CSBrain)

- **FEMBA** — *Tegon et al.*  
  [paper](https://arxiv.org/abs/2502.06438)

- **LaBraM++** *(codebook/tokenizer FM)* — *Barmpas et al.*  
  [paper](https://arxiv.org/abs/2505.16724)

- **LUNA** — *Döner, Ingolfsson, Benini, Li*  
  [paper](https://arxiv.org/abs/2510.22257) · [code](https://github.com/pulp-bio/biofoundation)

- **NeurIPT** — *Fang et al.*  
  [paper](https://arxiv.org/abs/2510.16548) · [NeurIPS page](https://neurips.cc/virtual/2025/poster/119245)

- **REVE** — *El Ouahidi et al.*  
  [paper](https://arxiv.org/abs/2510.21585) · [project](https://brain-bzh.github.io/reve/)

- **THD-BAR** — *Yang et al.*  
  [paper](#) · [code](#)

### 2024
- **CBraMod** — *Wang et al.*  
  [paper](https://arxiv.org/abs/2412.07236) · [code](https://github.com/wjq-learning/CBraMod) · [OpenReview](https://openreview.net/forum?id=NPNUHgHF2w)

- **EEGFormer** — *Chen et al.*  
  [paper](https://arxiv.org/abs/2401.10278)

- **LaBraM** — *Jiang et al.*  
  [paper](https://arxiv.org/abs/2405.18765)

- **Neuro-GPT** — *Cui et al.*  
  [paper](https://arxiv.org/abs/2311.03764) · [code](https://github.com/wenhui0206/NeuroGPT)

- **NeuroLM** — *Jiang et al.*  
  [paper](https://arxiv.org/abs/2409.00101)

### 2023
- **BIOT** — *Yang et al.*  
  [paper](https://arxiv.org/abs/2305.10351) · [code](https://github.com/ycq091044/BIOT)

### 2021
- **BENDR** — *Kostas, Aroca-Ouellette, Rudzicz*  
  [paper](https://arxiv.org/abs/2101.12037)

---

## Multimodal brainwave Foundation Models (EEG + other modalities)

### 2025
- **BrainOmni** *(EEG+MEG)* — *Xiao et al.*  
  [paper](https://arxiv.org/abs/2505.18185) · [code](https://github.com/OpenTSLab/BrainOmni)

---

## Non-EEG brainwave Foundation Models (intracranial / other modalities)

### 2023
- **BrainBERT** *(iEEG)* — *Wang et al.*  
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
