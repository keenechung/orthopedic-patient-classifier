# orthopedic-patient-classifier

## Introduction

- A multi-class classification machine learning model that predicts disc hernia (Herniated Disc) or spondylolisthesis in orthopedic patients using six biomechanical data points.

## Information

- Each patient is represented in the data set by six biomechanical attributes derived from the shape and orientation of the pelvis and lumbar spine (each one is a column):
    - pelvic incidence
    - pelvic tilt
    - lumbar lordosis angle
    - sacral slope
    - pelvic radius
    - grade of spondylolisthesis

## Data Distribution

- Total patients (310)
    - Normal patients (100)
    - Abnormal patients (210)
        - Patients with disc hernia (Herniated Disc) (60)
        - Patients with Spondylolisthesis (150)

## Methodology:

- Understand Datasets & Data cleaning
- Exploratory Data Analysis (EDA)
- Visualization
- Model Selection
- Data Preprocessing & Pipeline Building
- Model Training
- Model Prediction & Evaluation
- Model Comparison

## Requirements

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Acknowledgements

- https://www.kaggle.com/datasets/uciml/biomechanical-features-of-orthopedic-patients
- The original dataset was downloaded from UCI ML repository:
- Lichman, M. (2013). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. <br>
Irvine, CA: University of California, School of Information and Computer Science
- Files were converted to CSV

