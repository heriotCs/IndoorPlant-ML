# Indoor Plant Health and Growth Prediction

## Overview

This project applies machine learning and deep learning techniques to predict indoor plant health and growth using two data modalities: **tabular** sensor readings and **image** data. The pipeline covers the full ML workflow from exploratory analysis and preprocessing through clustering, baseline modeling, and neural network development.

---

## Notebook Structure

### 1. EDA and Preprocessing
**Folder:** [`R2_EDA_Preprocessing`](R2_EDA_Preprocessing/)

- **Tabular:** Data cleaning, feature selection, outlier removal, normalization
- **Image:** Visual inspection and preprocessing of labeled plant images
- **Goal:** Prepare both datasets for downstream clustering and modeling

---

### 2. Clustering
**Folder:** [`R2_Clustering`](R2_Clustering/)

- **Tabular:** K-Means applied to sensor data to identify natural groupings
- **Image:** Cluster analysis on visual features
- **Goal:** Surface natural patterns and conditions in plant health data

---

### 3. Baseline Models
**Folder:** [`R3_Baseline_Models`](R3_Baseline_Models/)

- **Tabular:** Logistic Regression, Decision Tree, KNN
- **Image:** Decision Trees, Naive Bayes, KNN
- **Goal:** Establish performance benchmarks before introducing deep learning

---

### 4. Neural Networks
**Folder:** [`R4_Neural_Networks`](R4_Neural_Networks/)

- Custom CNN trained on the image dataset
- Deep learning models for tabular prediction tasks

---

### 5. Archive
**Folder:** [`Archive`](Archive/)

Older dataset versions and notebook iterations retained for reference.

---

## Datasets

**Folder:** [`Datasets`](Datasets/)

- **Tabular:** Indoor sensor readings (temperature, humidity, soil moisture, and related features)
- **Image:** Labeled plant photographs covering a range of health conditions

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/heriotCs/DMML-GRP-14.git
   ```

2. Navigate to the project directory:
   ```bash
   cd DMML-GRP-14
   ```

3. Open the notebooks in Jupyter or VS Code and run them in order:
   - `R2_EDA_Preprocessing`
   - `R2_Clustering`
   - `R3_Baseline_Models`
   - `R4_Neural_Networks`
