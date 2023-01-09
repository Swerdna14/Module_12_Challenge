# Credit Risk Resampling
**Module 12 Challenge**

In this challenge, we were tasked to see how accurate a Logistic Regression Model was at predicting credit risk.

---

## Technologies

The credit risk resampling analysis leverages Python 3.8+ and utilizes the following project libraries and dependencies:
* [Pandas](https://github.com/google/pandas) - Pandas is a powerfull tool for data analysis and manipulation. Pandas provides a plethora of useful functions that make it easy to express, analyze, and manipulate data.

* [scikit-learn](https://scikit-learn.org/stable/) - This is a machine learning library for the python programming language. This library allows for the use of multiple machine learning models, tools, and algorithms.

---

## Installation Guide

In order to use this program please import and utilize the following libraries and dependencies: 

```python
import numpy as np
import pandas as pd
from pathlib import Path
from sklearn.metrics import balanced_accuracy_score
from sklearn.metrics import confusion_matrix
from imblearn.metrics import classification_report_imbalanced
```

---  

### **Run instructions:**
To run this analysis, simply clone the repository or download the files. Open a terminal instance and start a jupyter lab instance by using the following command:
```python
jupyter lab
```
Once it has opened, navigate to the file named **credit_risk_resampling.ipynb**.

---

## Results

 It was shown that the model had a 100% accuracy when predicting healthy loans while it was only 85% accurate predicting high-risk loans.

We then oversampled the data to see if there was any difference. It in fact made it better at predicting high-risk loans overall by 3%, with the f1 score moving from the original 88% to 91% with the oversampled data.

---

## Contributors

This project was created as part of the module 14 challenge in the Monash University Fintech Bootcamp 2022 Program by:

Lachlan Andrews

Email: swerdna14@gmail.com

LinkedIn: lachlanjandrews
