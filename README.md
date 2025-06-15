# Metric Space Creation for Oxide Catalysts using Machine Learning

This project analyzes the physicochemical properties of oxide catalysts using machine learning to identify patterns, similarities, and clusters within the dataset. It involves data preprocessing, normalization, dimensionality reduction, clustering, and visualization in 2D and 3D space.

## 📁 Dataset
The dataset contains features like:
- Band Gap
- Formation Energy
- Catalytic Activity
- Crystal Structure (One-hot encoded)
- Catalyst ID

## 🧪 Tools Used
- Python
- Pandas, NumPy
- scikit-learn (for scaling, PCA, K-Means, and t-SNE)
- Matplotlib, Seaborn (for visualization)

## 🚀 Workflow
1. **Data Cleaning and Feature Engineering**  
   Load and process catalyst data including encoding categorical features and scaling.

2. **Dimensionality Reduction**  
   - PCA (Principal Component Analysis)
   - t-SNE (t-distributed Stochastic Neighbor Embedding)

3. **Clustering**  
   K-Means clustering used to form groups based on feature similarity.

4. **Visualization**  
   - 2D PCA scatter plots  
   - 3D t-SNE plot for better spatial understanding  
   - Correlation heatmaps

## 📊 Visual Outputs
- **2D PCA**: Shows separability of catalysts based on key features.
- **3D t-SNE**: Interactive view of catalyst clusters.
- **Heatmaps**: Correlation between physicochemical properties.

## 📂 Files Included
- `oxide_metric_space_large_dataset_with_tsne.ipynb`: Main Jupyter Notebook with code and visualizations.
- `README.md`: This file.

## 📌 How to Run
1. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
