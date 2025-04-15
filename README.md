# Kidney Disease Prediction Project

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0+-orange)
![Pandas](https://img.shields.io/badge/Pandas-1.3+-brightgreen)

A machine learning project to predict chronic kidney disease (CKD) using clinical parameters.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Model Performance](#model-performance)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project compares multiple machine learning models to predict chronic kidney disease based on 25 clinical features including blood tests, urine analysis, and patient history. The best-performing model achieved *99.17% accuracy*.

## Dataset
*Source:* kidney_disease.csv  
*Samples:* 400 patients  
*Features:* 25 clinical parameters  
*Target:* Binary classification (CKD vs non-CKD)

Key features include:
- Blood pressure
- Specific gravity
- Albumin
- Serum creatinine
- Hemoglobin

## Model Performance
| Rank | Model                   | Accuracy Score |
|------|-------------------------|----------------|
| 1    | Extra Trees Classifier  | 0.991667       |
| 2    | Random Forest Classifier| 0.983333       |
| 3    | Decision Tree Classifier| 0.975000       |
| 4    | KNN                     | 0.666667       |

## Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/kidney-disease-prediction.git
cd kidney-disease-prediction
Results
The Extra Trees Classifier outperformed other models with:

99.17% accuracy

Excellent recall (minimizing false negatives)

Robust feature importance analysisContributing
Contributions are welcome! Please:

Fork the project

Create your feature branch

Submit a pull request
