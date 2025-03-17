# Titanic Dataset Exploration

### Link to notebook: [ml02_neely.ipynb](https://github.com/bncodes19/applied-ml-bneely/blob/main/lab02/ml02_neely.ipynb)

## Overview
In the analyis, the Titanic dataset from Seaborn is analyzed. Initial exploration calculations are performend, data is cleaned, and columns are created through feature engineering. Lastly data is split through stratification with selected features and a target variable.

## Sections of the analysis:
- Section 1: Import and Inspect the Data
- Section 2: Data Exploration and Preparation
   - 2.1: Exploring data patterns and distributions through visualizations
   - 2.2: Handle Missing Values and Clean Data
   - 2.3: Feature Engineering
- Section 3: Feature Selection and Justification
   - 3.1: Choose features and target
- Section 4: Splitting

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

## Professional Python Setup and Workflow
We follow professional Python practices. 
Full instructions are available at <https://github.com/denisecase/pro-analytics-01/>. 
A concise version is provided at [WORKFLOW_GUIDE.md](./docs/WORKFLOW_GUIDE.md)

**Important:** VS Code + Pylance may fail to recognize installed packages in Jupyter notebooks.  
See the above guides for troubleshooting and solutions.  

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