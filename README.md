# Pose-aware Multimodal Graph-Transformer with Contrastive Pretraining  

## 📌 Project Idea  
This repository presents the **project proposal** for developing a novel framework for **drug–target binding affinity (DTA) prediction**.  
Currently, this is only an idea, and no implementation code is available yet.  

The proposed model, **Pose-aware Multimodal Graph-Transformer (PMG-Transformer)**, aims to integrate multiple complementary modalities to better capture the complex nature of biochemical interactions.  

---

## 🚀 Motivation  
Accurate drug–target binding affinity prediction is a cornerstone of computational drug discovery.  
While recent methods like **HGTDP-DTA** and **GraphCL-DTA** have shown promise, they often underutilize the structural and multimodal nature of biochemical data.  
This project proposes a unified architecture to bridge this gap.  

---

## 🧪 Proposed Approach  
The framework will combine:  
- 🧪 **Ligand 2D graph structures**  
- 🧬 **Protein sequence embeddings**  
- 📐 **3D docking pose geometry**  

Core components:  
- **Graph-Transformer Backbone** → Learns expressive molecular and protein representations.  
- **Dynamic Cross-Attention** → Enables cross-modality information flow.  
- **Contrastive Pretraining** → Aligns representations across ligand, protein, and docking views before fine-tuning.  

---

## 📊 Expected Outcomes  
- Improved performance on **Davis** and **KIBA** datasets.  
- Lower **Root Mean Squared Error (RMSE)**.  
- Higher **Concordance Index (CI)**.  
- Outperforming baselines such as **HGTDP-DTA** and **GraphCL-DTA**.  

---

## 📚 References  
- Davis et al., 2011 – *Kinase inhibitor selectivity profiling using quantitative DTA measurements*  
- Tang et al., 2022 – *HGTDP-DTA: Heterogeneous Graph Transformer for DTA prediction*  
- Wang et al., 2021 – *GraphCL-DTA: Contrastive Learning for DTA prediction*  

---

## 👥 Contributors  
- **Sheraz Ahmad** – Concept & Proposal  

---

## 📜 License  
This project idea is shared under the **MIT License**.  
