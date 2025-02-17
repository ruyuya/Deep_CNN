1. Introduction:

Problem Description:
The goal of this project is to develop a deep learning model to detect metastatic cancer in histopathologic scans of lymph node sections. The dataset consists of small image patches extracted from larger digital pathology scans. Each image is labeled as either containing cancer (label = 1) or not (label = 0). The task is binary classification, and the model's performance is evaluated using accuracy, AUC (Area Under the Curve), and other classification metrics.

Dataset Overview:
Training Data: 220,025 labeled images (96x96 pixels) in RGB format.
Test Data: 57,458 unlabeled images for predictions.
Labels: A CSV file mapping image IDs to binary labels (0 = no cancer, 1 = cancer).

The dataset is imbalanced, with approximately 60% of the images labeled as negative (no cancer) and 40% as positive (cancer).

Reference:
The dataset is sourced from the [Histopathologic Cancer Detection competition on Kaggle](https://www.kaggle.com/c/histopathologic-cancer-detection). 
