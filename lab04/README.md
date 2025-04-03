# Titanic Dataset Survival Prediction

### Link to notebook: [ml04_neely.ipynb](https://github.com/bncodes19/applied-ml-bneely/blob/main/lab04/ml04_neely.ipynb)

## Overview
In this lab, the Titanic dataset from Seaborn is analyzed. 

Four types of regression models models are employed for predicting fare:
- Linear Regression
- Ridge Regression (L2 Penalty)
- Elastic Net (L1 + L2 combined)
- Polynomial Regression

## Sections of the analysis:
- Section 1: Import The Dataset and Inspect the Data
- Section 2: Data Exploration and Preparation
   - 2.1: Handle Missing Values and Clean Data
- Section 3: Feature Selection and Justification
   - 3.1: Choose features and target
- Section 4: Train a Regression Model (Linear Regression)
   - 4.1 Split the Data
   - 4.2 Train and Evaluate Linear Regression Models for all four cases
   - 4.3 Report Performance
- Section 5: Compare Alternative Models
   - 5.1 Evaluate Ridge Regression (L2 penalty) for the best case (Case 4)
   - 5.2 Evaluate Elastic Net (L1 + L2 combined) for the best case (Case 4)
   - 5.3 Evaluate Polynomial Regression for the best case (Case 4)
   - 5.4 Visualize Polynomial Cubic Fit (for 1 inpute feature)
   - 5.5 Compare All Models
   - 5.6 Visualize Higher Order Polynomial (for the same 1 input case)
- Section 6: Final Thoughts
   - 6.1 Summarize Findings
   - 6.2 Discuss Challenges

## Dataset 
Titanic dataset
- We use the built-in dataset from seaborn:  
   - `import seaborn as sns`
   - `titanic = sns.load_dataset('titanic')`  

## Python Library for Machine Learning: scikit-learn
We use scikit-learn, built on NumPy, SciPy, and matplotlib
   - Read more at <https://scikit-learn.org/>
   - Scikit-learn supports classification, regression, and clustering.
   - This project applies regression.

**Important:** Use a 2-step installation to avoid timeouts and partial installs:  
1. **First Install:** Install from `requirements.txt` with `scikit-learn` commented out.  
2. **Second Install:** Uncomment `scikit-learn` and rerun the install command.

---

## How to clone this project for further development:
Clone this repository:  
```shell
git clone <https://github.com/bncodes19/applied-ml-bneely/tree/main>
```
### To set up the virtual environment in the terminal:
``` shell
python3 -m venv .venv
```
4. Activate the virtual enivronment
``` shell
source .venv/bin/activate
```