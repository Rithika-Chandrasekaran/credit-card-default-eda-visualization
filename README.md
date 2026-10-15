# credit-card-default-eda-visualization
# Credit Card Default: EDA, Visualization and Deep Learning

**Course:** U21ADP05 Exploratory Data Analysis and Visualization (Assignment II)
**Student:** RITHIKA C, 24AD092, AI & DS, KPR Institute of Engineering and Technology

## Overview
Exploratory analysis and visualization of the Default of Credit Card Clients dataset
(30,000 clients, 23 features), followed by an MLP that predicts default next month.

## Dataset
KAGGLE : https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset
(downloaded programmatically in the notebook; copies are in `data/`)

## Methods
1. EDA and cleaning (duplicates, undocumented codes, IQR capping)
2. Feature engineering, encoding, standardization, 70/15/15 stratified split
3. 10 visualizations covering the 7 stages of visualization
4. Keras MLP with class weights, grid-search tuning and permutation importance
5. Evaluation: loss/accuracy/AUC curves, confusion matrix, ROC, threshold analysis

## Key results
| Model | ROC AUC | Recall | F1 |
|---|---|---|---|
| MLP | [ ] | [ ] | [ ] |
| Logistic Regression | [ ] | [ ] | [ ] |
| Random Forest | [ ] | [ ] | [ ] |

Main finding: [one sentence, e.g. repayment history is the dominant predictor].

## How to run
Open `notebooks/EDA_Credit_Default.ipynb` in Google Colab and run all cells.
Local: `pip install -r requirements.txt`.

## References
See the project report.
