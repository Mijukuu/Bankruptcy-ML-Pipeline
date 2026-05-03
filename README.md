# Cluster-Based Bankruptcy Prediction

End-to-end machine learning pipeline for predicting company bankruptcy using clustering, feature selection, and stacking ensembles.

## Key Features
- KMeans-based segmentation of companies
- Cluster-specific modeling
- Stacking ensemble architecture
- Reproducible preprocessing pipeline

## ⚙️ Environment & Reproducibility

This project uses saved preprocessing pipelines and models (`joblib` files) that were trained using:

- scikit-learn == 1.6.1

To ensure compatibility, please install dependencies using:

```bash
pip install -r requirements.txt
