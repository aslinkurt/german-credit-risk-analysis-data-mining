# German Credit Risk Analysis

This project explores and evaluates multiple data mining techniques to predict credit risk using the German Credit dataset. It applies Logistic Regression, Classification Trees, and Neural Networks to identify the best-performing model based on accuracy, sensitivity, and financial net profit.

## 📊 Project Overview

- **Dataset**: [UCI German Credit Dataset](https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data))
- **Observations**: 1000 applicants  
- **Variables**: 30 predictors + 1 response variable (Good/Poor Credit)

## 🧠 Techniques Used

1. **Logistic Regression**
   - GLM with optimized cutoff
   - Confusion matrix on validation set

2. **Classification Trees**
   - Pruned decision tree model
   - Validation results

3. **Neural Networks**
   - Multi-layer perceptron model
   - Model performance on unseen data
  
4. K-NN

## 💡 Key Findings

- Variables such as **employment**, **loan purpose**, and **housing** showed high predictive power.
- Logistic Regression yielded the **highest net profit**, with optimal balance between sensitivity and specificity.
- Careful variable transformation and grouping (e.g., merging vehicle types or education categories) improved model performance.

## 📈 Model Comparison

| Technique             | Accuracy | Sensitivity | Net Profit |
|----------------------|----------|-------------|------------|
| Logistic Regression  | ✔️ Highest | ✔️ Highest   | ✔️ Highest  |
| Classification Tree  | Moderate | Moderate    | Lower      |
| Neural Network       | High     | Moderate    | Moderate   |

## 📁 Files

- `GBA_6210_Group_Project_FINALIZED.Rmd`: R Markdown source with all analysis
- `GBA_6210_Group_10_German_Credit_Case_Study_Analysis.pptx`: Summary presentation of project findings

## 🚀 How to Run

To replicate the results:

1. Clone this repo:
   ```bash
   git clone https://github.com/aslinkurt/german-credit-risk-analysis-data-mining.git

