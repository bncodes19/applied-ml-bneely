# Wine Quality Prediction

### Link to notebook: [ensemble-neely.ipynb](https://github.com/bncodes19/applied-ml-bneely/blob/main/lab05/ensemble-neely.ipynb)

## Overview
In this lab, the Wine Quality dataset from the UCI Machine Learning Repository is analyzed. 

Two types of models are employed for predicting wine quality:
- AdaBoost (100)
- MLP Classifier

## Sections of the analysis:
- Section 1: Import The Dataset
- Section 2: Prepare the Data
- Section 3: Feature Selection and Justification
- Section 4: Split the Data into Train and Test
- Section 5: Evaluate Model Performance using Adaboost anad MLP Classifier 
- Section 6: Compare Results
- Section 7: Conclusions and Insights

## Dataset 
Wine Quality Dataset
[winequality-red.csv](https://github.com/bncodes19/applied-ml-bneely/blob/main/lab05/winequality-red.csv)

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