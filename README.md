# Telecom Customer Segmentation Analysis

## Project Overview
This project focuses on customer segmentation analysis for a telecom company using machine learning techniques. The analysis is performed on a dataset containing 60,000 customers with 167 different features (sample of 100 rows shown in repository).

## Methodology

### 1. Customer Segmentation (Clustering)
- **Dimensionality Reduction**: Applied PCA (Principal Component Analysis) to handle feature correlation and reduce dimensionality
- **Segmentation**: Implemented Gaussian Mixture Model (GMM) for customer segmentation
- **Optimal Cluster Selection**: Used AIC and BIC metrics to determine the optimal number of segments
- **Visualization**: Employed UMAP and PCA for segment visualization and interpretation

### 2. Segment Characterization
- **Feature Importance Analysis**: 
  - Implemented Random Forest Classifier and XGBoost Classifier
  - Identified most distinctive features for each segment (one-vs-rest approach)
  - Generated segment profiles based on key characteristics

### 3. Sub-segmentation (In Progress)
- Further division of each main segment into three sub-segments using GMM
- Detailed analysis of sub-segment characteristics

### 4. Offer Creation (In Progress)
- Creating targeted marketing strategies based on segment characteristics
- Developing personalized product recommendations

## Technologies Used
- **Programming Language**: Python
- **Data Processing**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Statistical Analysis**: StatsModels, SciPy
- **Machine Learning**: scikit-learn, XGBoost
- **Data Storage**: Excel