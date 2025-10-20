# 📚 References – PlantCLEF 2025 Project

This directory contains key reference documents and research papers used in the **IN22-S5-EN3160 Project – PlantCLEF 2025: Multi-Label Plant Species Prediction from Quadrat Images**.  
These materials include competition-winning solution reports and foundational research on Vision Transformer models utilized in this project.

---

## 📁 Included Files

| File | Description |
|:------|:-------------|
| **DINO.pdf** | Research paper on the DINO and DINOv2 self-supervised Vision Transformer (ViT) model. This pretrained model was provided by the PlantCLEF 2025 organizers and serves as the **feature extraction backbone** for our experiments. |
| **2nd Place Solution.pdf** | Official summary of the **second-place solution** by team *DS@GT*. It presents a **training-free**, tile-based ViT pipeline leveraging **domain-prior adaptation** using **visual-cluster Bayesian priors**. Achieved a private leaderboard score of **0.348**. |
| **3rd Place Solution.pdf** | Official summary of the **third-place solution** by team *Chlorophyll Crew*. It introduces a **multi-head Vision Transformer (Hydra model)** approach combining **species, genus, and family-level classification** with metadata-driven fusion. Achieved a private leaderboard score of **0.33655**. |

---

## 🧠 Summary of Key Papers

### 1. DINO Vision Transformer (ViT)
- **Purpose:** Foundation for the pretrained model used in PlantCLEF 2025.
- **Concept:** DINO (Distillation with No Labels) introduces a **self-supervised learning** method where a Vision Transformer learns visual representations without labeled data.
- **Relevance:** The **DINOv2 ViT-B/14** backbone was provided by the challenge organizers and used as the **frozen feature extractor** for both baseline and advanced models.

---

### 2. 2nd Place – DS@GT Solution Summary

- **Approach:** A **training-free, zero-shot inference** pipeline using the fine-tuned `ViTD2PC24All` Vision Transformer model.
- **Key Techniques:**
  - **Tiled inference** (4×4 grid) aligning tile size with ViT receptive field.
  - **Visual-cluster Bayesian priors** via unsupervised clustering of embeddings to reweight class probabilities.
  - **Geolocation filtering** to restrict predictions to plausible regional species.
- **Outcome:** Best private leaderboard score – **0.34834**, demonstrating that domain-prior adaptation significantly mitigates dataset domain shift.

---

### 3. 3rd Place – Chlorophyll Crew Solution Summary

- **Approach:** **Multi-head Hydra Vision Transformer** leveraging **DINOv2 ViT-B/14** as a frozen backbone.
- **Key Innovations:**
  - **Taxonomic fusion** combining predictions across species, genus, and family heads.
  - **Multi-scale tiling** (4×4, 5×5 grids) and **dynamic thresholding** for adaptive confidence filtering.
  - **Bagging and ensemble averaging** to enhance prediction robustness.
- **Outcome:** Private leaderboard score – **0.33655**, demonstrating strong results with a taxonomy-aware fusion strategy.

---

## 📎 Usage

These documents serve as foundational references for:
- Understanding **baseline and advanced models** in PlantCLEF 2025.
- Designing experiments and architectures within the `notebooks/` folder.
- Benchmarking results against **top-performing approaches** from the official competition.

---

## 🧩 Notes

- The PDFs are kept in this folder for academic reference and model comparison purposes.
- Please cite the respective papers and competition reports if directly referenced in project documentation or presentations.
- DINO and DINOv2 papers are publicly available under Meta AI Research.

---

> **Recommended Citation Example:**  
> PlantCLEF 2025 Challenge References. (2025). *Kaggle Competition – Multi-label Plant Species Prediction from Quadrat Images*. Retrieved from [https://www.kaggle.com/competitions/plantclef-2025](https://www.kaggle.com/competitions/plantclef-2025)

---

