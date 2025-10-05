# In22-S5-EN3160-Project---PlantCLEF2025
Multi-label Plant Species Prediction from Quadrat Images 

Challenge link - https://www.kaggle.com/competitions/plantclef-2025 

### Context
Vegetation plot inventories play a crucial role in ecological studies, providing standardized sampling methods for biodiversity assessment, long-term monitoring, and large-scale remote surveys. These inventories generate valuable data for ecosystem analysis, biodiversity conservation, and evidence-based environmental decision-making.

A typical inventory consists of multiple quadrats—small vegetation sampling areas of about 0.5 square meters—where botanists meticulously identify all plant species present. In addition to species identification, they also measure species abundance using indicators such as biomass, specific ecological scores, and the proportion of area occupied in images.

### The Challenge

Integrating AI into this process could significantly improve efficiency, allowing for broader ecological studies with reduced expert effort. However, developing AI models for this multi-label classification task remains a major challenge.

Ideally, training a robust model would require a large dataset of quadrat images labeled with all plant species present. However, collecting and annotating such data at scale would be an enormous task, given the thousands of species within a single flora. In contrast, vast datasets of individual plant images are already available, making it easier to train highly efficient classification models on them.

### PlantCLEF 2025 Challenge

The PlantCLEF 2025 challenge aims to bridge this gap by evaluating models that predict the species present in quadrat images, using a training set composed of single-label images of individual plants.

In other words, the task is framed as a multi-label classification problem, where the goal is to predict all plant species present in high-resolution quadrat images. The main difficulty lies in the domain shift between the training data (single-label images of individual plants) and the test data (multi-label, high-resolution vegetation images).

<img width="1010" height="522" alt="image" src="https://github.com/user-attachments/assets/79cfaaf9-7299-4fd0-8482-642967ad447c" />


