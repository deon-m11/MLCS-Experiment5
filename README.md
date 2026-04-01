# Machine Learning in Malware Detection and Penetration Testing

MLCS Lab Case Study | K.J. Somaiya College of Engineering | 2025-26

## Overview
Implementation of multiple ML models for detecting malware using PE (Portable Executable) file header features. The system classifies executables as **Malware** or **Legitimate** using supervised learning.

## Dataset
- **ClaMP** (Classification of Malware with PE headers)
- Source: [GitHub](https://raw.githubusercontent.com/urwithajit9/ClaMP/master/ClaMP_Integrated-5184.csv)
- 5,184 samples | PE header features | Binary classification (Malware vs Legitimate)

## Models Implemented
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Gradient Boosting

## Experiments
| Exp | Title |
|-----|-------|
| 3 | Real-time Data Collection & Training |
| 4 | Data Preparation & Visualization |
| 5 | ML System & Performance Comparison |

## How to Run
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
jupyter notebook
```
Open the notebook and run all cells.

## Tech Stack
Python, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn
