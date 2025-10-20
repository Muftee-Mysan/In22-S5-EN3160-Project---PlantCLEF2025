# 🌿 Images – Visualization Outputs (PlantCLEF 2025)

This folder contains visual outputs and analysis figures generated during the **IN22-S5-EN3160 Project – PlantCLEF 2025: Multi-Label Plant Species Prediction from Quadrat Images**.  
The images illustrate key aspects of model inference, tiling strategies, embedding visualization, and threshold tuning.

---

## 📁 Included Files

| File | Description |
|:------|:-------------|
| **min_score_comparison_topk_predictions.png** | A performance plot showing the **effect of minimum score thresholds** on the number of valid Top-k predictions. It illustrates how stricter confidence thresholds reduce the number of accepted predictions while improving accuracy. |
| **quadrat_predictions.jpeg** | Sample **quadrat images with model-predicted species labels**. Each image patch represents a real-world quadrat from the dataset, showcasing how the model identifies multiple plant species from a single input. |
| **Tiling.png** | Visualization of the **tiling strategy** applied to quadrat images. The image is divided into smaller tiles (e.g., 4×4 or 5×5 grids) for inference using the Vision Transformer (ViT) model, improving spatial feature extraction. |
| **tsne_GUARDEN-AMB-CF21-1-10-2024-0326.jpeg** | **t-SNE embedding visualization** of feature vectors extracted by the ViT model. It displays the clustering of semantically similar plant species, confirming that the DINO-based embeddings preserve discriminative plant features. |

---

## 🧠 Purpose of These Visuals

These figures were generated to:
- Visualize **how the model perceives and segments quadrat images**.
- Analyze **feature embeddings** using **t-SNE dimensionality reduction**.
- Evaluate **threshold-dependent prediction performance**.
- Demonstrate the **effectiveness of the ViT tiling approach** for multi-label classification.

---

## 🧩 Folder Usage

Include this folder when:
- Submitting the final project repository.
- Preparing visual materials for presentations or reports.
- Demonstrating the **visual interpretability** and **evaluation process** of the PlantCLEF 2025 solution.

---

## 🪶 Notes

- All visualizations were produced using Jupyter notebooks within the `/notebooks` directory.
- Images are **compressed for sharing** and should not be used for retraining.
- For reproducibility, refer to notebook logs corresponding to visualization generation dates.

---

> **Project:** PlantCLEF 2025 – Multi-Label Plant Species Prediction  
> **Team:** IN22-S5-EN3160  
> **Department of Electronic and Telecommunication Engineering**  
> **University of Moratuwa – 2025**

---

