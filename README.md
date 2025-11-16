# ML Project 2025

## Project Overview
This project implements machine learning models on two types of datasets as required:

1. **Numerical Dataset**: Healthcare Insurance Expenses  
   - Models: Linear Regression & KNN Regression  
   - Goal: Predict healthcare expenses  

2. **Image Dataset**: Fruits 360 (5 selected classes)  
   - Models: Logistic Regression & KMeans  
   - Goal: Classify images of fruits into 5 categories  

---

## Folder Structure
```css
ML-Project-2025/
│
├── datasets/
│   ├── numerical/
│   │   └── insurance.csv
│   └── images/
│       ├── class1/
│       ├── class2/
│       ├── class3/
│       ├── class4/
│       └── class5/
│
├── numerical/
│   ├── preprocessing.py
│   ├── linear_regression.py
│   └── knn_regression.py
│
├── image/
│   ├── preprocessing.py
│   ├── logistic_regression.py
│   └── kmeans.py
│
├── results/
│   ├── numerical/
│   │   ├── linear_regression_loss_curve.png
│   │   ├── knn_regression_loss_curve.png
│   │   └── metrics.txt
│   └── image/
│       ├── logistic_confusion_matrix.png
│       ├── logistic_roc.png
│       ├── kmeans_clusters.png
│       └── metrics.txt
│
├── docs/
│   ├── Cover_Sheet.pdf
│   ├── Project_Description.pdf
│   └── README_INSTRUCTIONS.txt
│
├── notebooks/
│   ├── numerical_EDA.ipynb
│   └── image_EDA.ipynb
│
├── README.md
└── requirements.txt
```

---

## How to Run
#### 1. Install required libraries:

```bash
pip install -r requirements.txt
```
#### 2. Numerical Models:

```bash
cd numerical
python preprocessing.py
python linear_regression.py
python knn_regression.py
```  
   - Ensure the `insurance.csv` file is in the `datasets/numerical/` directory.


#### 3. Image Models:

```bash
cd image
python preprocessing.py
python logistic_regression.py
python kmeans.py

```
   - Ensure the image dataset is structured correctly in `datasets/images/` with subfolders for each class.

#### 4. Results:
   - After running the scripts, results will be saved in the `results/` directory.
   - For numerical models, check `results/numerical/`.
   - For image models, check `results/image/`.
   - All plots and evaluation metrics are saved in the `results/` folder.