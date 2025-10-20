# 🌿 Notebooks – PlantCLEF 2025 Project

This directory contains all Jupyter notebooks developed for the **IN22-S5-EN3160 Project – PlantCLEF 2025: Multi-label Plant Species Prediction from Quadrat Images**.  
Each notebook corresponds to a specific stage in the workflow — from tiling and model design to inference and aggregation.

---

## 📁 Notebook Overview

| No. | Notebook Name | Description |
|:---:|:----------------------------|:----------------------------|
| **1** | `1. Inferencing on test data.ipynb` | Performs inference on the provided test dataset using the trained multi-label model. Outputs predictions ready for submission to Kaggle. |
| **2** | `2. Inferencing on a single image.ipynb` | Used for quick evaluation or debugging. Runs inference on a single quadrat image to visualize model performance and predicted species. |
| **3** | `3. Introduction to Tiling.ipynb` | Demonstrates the tiling concept used to handle large quadrat images by dividing them into smaller patches for efficient model inference. |
| **4** | `4. Tiling Techniques.ipynb` | Implements the initial version of the tiling pipeline with image segmentation, patch extraction, and visualization. |
| **5** | `5. Tiling Techniques Continued.ipynb` | Improves on previous tiling by optimizing patch selection and handling overlapping areas between tiles. |
| **6** | `6. Aggregation Techniques.ipynb` | Combines predictions from multiple tiles or models to produce a single aggregated prediction per quadrat image (ensemble/post-processing). |
| **7** | `7. Tiling Inference – Post Aggregation.ipynb` | Demonstrates the full inference workflow with tiling and aggregation combined for improved final accuracy. |
| **8** | `8. Tiling Inference – Post Aggregation Continued.ipynb` | Refines and evaluates different aggregation strategies, comparing performance metrics (precision, recall, F1-score). |
| **9** | `9. Model Architecture.ipynb` | Defines and visualizes the deep learning architecture used for the task (e.g., EfficientNet, ConvNeXt). Includes model summary and parameter tuning steps. |

---

## ⚙️ How to Use

1. **Environment Setup**
   ```bash
   pip install -r ../requirements.txt


