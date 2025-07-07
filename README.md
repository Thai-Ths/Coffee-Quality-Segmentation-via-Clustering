# Coffee Quality Segmentation via Clustering

This project applies unsupervised machine learning to analyze and segment coffee samples based on sensory and chemical quality attributes. Using clustering techniques on a publicly available dataset from the Coffee Quality Institute (CQI), the analysis reveals hidden patterns and actionable groupings that can benefit coffee producers, sellers, and quality control professionals.

---

## Dataset

- **Source:** [Kaggle - Coffee Quality Data (CQI)](https://www.kaggle.com/datasets/fatihb/coffee-quality-data-cqi)
- **Contents:** Over 1,300 samples with features such as country, processing method, altitude, cup scores (aroma, flavor, acidity, etc.), moisture, and more.

---

## Approach

1. **Data Exploration & Cleaning:**  
   - Preview and assess raw data for structure and quality.
   - Handle missing values, encode categorical features, and engineer new features.

2. **Exploratory Data Analysis (EDA):**  
   - Visualize relationships between quality scores, altitude, origin, and other features.
   - Detect and address outliers.

3. **Preprocessing:**  
   - Select relevant features.
   - Scale numeric variables to ensure fair clustering.

4. **Clustering:**  
   - Apply KMeans clustering to segment coffees by quality profile.
   - Determine optimal cluster count using the elbow method.
   - Visualize and interpret cluster assignments.

5. **Insights & Conclusions:**  
   - Summarize the key characteristics of each cluster.
   - Identify actionable patterns for coffee industry stakeholders.

---

## Results

- The clustering analysis identified distinct groups of coffees with meaningful differences in overall quality and sensory scores.
- Principal Component Analysis (PCA) and feature importance evaluation provided further validation and interpretability of clusters.
