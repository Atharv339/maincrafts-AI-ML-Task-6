# maincrafts-AI-ML-Task-6
# Customer Segmentation Analysis — Unsupervised Machine Learning

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E.svg)](https://scikit-learn.org/)
[![Internship](https://img.shields.io/badge/Maincrafts-Task%206-brightgreen.svg)](https://maincrafts.com/)

An unsupervised learning project performing behavioral customer segmentation using K-Means and Agglomerative Hierarchical Clustering to inform targeted marketing strategies.

---

## Project Structure
- `Task_6_Customer_Segmentation.ipynb`: Complete exploratory data analysis, cluster evaluation, and modeling workflow.
- `requirements.txt`: Python package dependencies.
- `README.md`: Project summary, methodology, and strategic insights.

## Methodology
1. **Exploratory Data Analysis & Scaling**: Standardized `Annual Income` and `Spending Score` with `StandardScaler`.
2. **K Selection**:
   - **Elbow Method (WCSS)**: Identified optimal elbow bend at $k=5$.
   - **Silhouette Analysis**: Confirmed peak cluster separation at $k=5$ (Score: ~0.55).
3. **Modeling & Benchmarking**:
   - Evaluated **K-Means** against **Hierarchical Agglomerative Clustering (Ward Linkage)** across Silhouette Score, Davies-Bouldin Index, and Calinski-Harabasz Index.
4. **Actionable Personas**: Defined 5 operational customer segments ranging from Frugal Savers to VIP / Elite shoppers.

## Setup & Execution
```bash
git clone [https://github.com/](https://github.com/)<your-username>/Maincrafts_AI_ML_Task6.git
cd Maincrafts_AI_ML_Task6
pip install -r requirements.txt
jupyter notebook Task_6_Customer_Segmentation.ipynb
