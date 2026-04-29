# Maternal Health Visualization

## Overview
This project focuses on high-dimensional visualization techniques used to explore and interpret latent maternal profiles derived from the 2024 U.S. Birth dataset. The goal is to better understand the underlying structure of maternal health data by examining complex, multivariate relationships across pre-delivery characteristics.

This repository complements a broader analytical project on latent maternal profiles by emphasizing visualization as a primary tool for interpreting clustering results and uncovering patterns that are not readily observable through traditional statistical methods.

---

## Key Objectives
- Visualize high-dimensional maternal health data  
- Interpret latent profiles identified through clustering  
- Compare how different visualization techniques represent data structure  
- Highlight both global and local patterns within complex datasets  

---

## Methods and Techniques
The following techniques are implemented:

- **Principal Component Analysis (PCA)** – captures global variance structure  
- **K-Means Clustering** – identifies latent maternal profiles  
- **t-Distributed Stochastic Neighbor Embedding (t-SNE)** – highlights local relationships  
- **Uniform Manifold Approximation and Projection (UMAP)** – balances global and local structure  
- **Parallel Coordinates Plots** – enables multivariate feature comparison across profiles  

---

## Repository Structure

- `01_data_preprocessing.ipynb`  
  Data cleaning, feature engineering, and preparation of pre-delivery variables  

- `02_clustering_visualization.ipynb`  
  PCA, K-Means clustering, and visualization of maternal profiles using multiple techniques  

---

## Data Access
The dataset used in this project is publicly available through the National Center for Health Statistics (NCHS):

https://www.cdc.gov/nchs/data_access/vitalstatsonline.htm

Due to the size of the dataset, it is not included in this repository. Users must download the dataset from the source and update file paths within the notebooks accordingly.

---

## How to Run

1. Download the dataset from the NCHS website  
2. Update file paths in each notebook to match your local environment  
3. Run the notebooks in the following order:
   - `01_data_preprocessing.ipynb`
   - `02_clustering_visualization.ipynb`

---

## Tools and Libraries
This project was developed using Python and the following libraries:

- pandas  
- NumPy  
- scikit-learn  
- matplotlib  
- seaborn  
- plotly  
- umap-learn  

---

## Notes
- This repository focuses on visualization and interpretation of high-dimensional data  
- Clustering is used to support visualization and profile identification  
- Interactive visualizations are implemented using Plotly for enhanced exploration  

---

## Related Work
This repository complements a broader project on latent maternal profile analysis, which includes additional statistical modeling and analysis.

---

## Author
Ariana Baker  
M.S. Biomedical Data Science  
Meharry Medical College
