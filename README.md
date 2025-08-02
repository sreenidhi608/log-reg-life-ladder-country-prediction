
## 📊 Dataset

- **Source**: [World Happiness Report 2018](https://worldhappiness.report/)
- **File**: `WHR2018Chapter2OnlineData.csv`
- **Attributes**:
  - Country name
  - Year
  - Life Ladder (target variable)
  - GDP per capita
  - Social support
  - Healthy life expectancy
  - Freedom to make life choices
  - Generosity
  - Perceptions of corruption
  - etc.

## 🎯 Problem Statement

The goal is to **predict the Life Ladder score** of each country using logistic regression.

## 🧠 ML Approach

- **Model**: Logistic Regression
- **Steps**:
  - Data loading and preprocessing
  - Feature selection and scaling
  - Model training and evaluation
  - Adding more complex models like ensemble models
  - Analyzing + comparing performance across models 

## ✅ Results

- The model provides a baseline for predicting countries' happiness scores.
- Accuracy metrics and example predictions are included in the notebook.

## 🛠️ Requirements

You can install required packages using the below and then run notebook DefineAndSolveMLProblem.ipynb:

```bash
pip install pandas numpy matplotlib scikit-learn
