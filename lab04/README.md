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
- Section 1: Import the Dataset
- Section 2: Data Exploration and Preparation
   - 2.1: Handle Missing Values and Clean Data
   - 2.3: Feature Engineering
- Section 3: Feature Selection and Justification
   - 3.1: Choose features and target
- Section 4: Train a Classification Model (Decision Tree)
   - 4.1 Split the Data
   - 4.2 Create and Train Decision Tree Model
   - 4.3 Predict and Evaluate Model Performance
   - 4.4 Confusion Matrix
   - 4.5 Decision tree Plot
   - 4.6 Repead Steps for 4.1-4.5 for Case 2
   - 4.7 Repead Steps for 4.1-4.5 for Case 3   
- Section 5: Alternative Model
   - 5.1 Train and Evaluate Model: Support Vector Machine
   - 5.2 Train and Evaluate Model: Neural Network - Multi Level Perceptron
- Section 6: Final Thoughts and Insights
   - 6.1 Summarize Findings
   - 6.2 Discuss Challenges Faced
   - 6.3 Next Steps

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