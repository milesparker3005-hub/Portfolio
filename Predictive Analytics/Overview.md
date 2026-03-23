
# Predictive Analytics Case
## Contents
- Final_code: The code used to conduct this case study
- Executive Summary: This breaks down every step of the process from identifying the business problem to making the model.
- Retention Data: Original dataset used 
## Business Problem
The business problem is to successfully identify what customers are likely to churn and what the major factors driving this are. This matters because it costs much more to acquire customers than it is to retain customers. If we can successfully predict who might churn, then we can employ targeted strategies, using insights from modeling, to retain those customers. 
## Key Results
* In general, the more people were referring others, the less they were churning 
* XGBoost was the best model (best ROC-AUC and significant "important features")
* Fiber Optics internet and Month-to-Month contracts were among the most important features across all model
## How to run the code
1. Open "case_comp_git.ipynb"
2. Run each individual cell block, starting with the first one that installs packages
3. The first group of blocks are exploratory data analysis and data preprocessing
4. After that are the three different models
5. After you run the code for each model, you can see the ROC-AUC score along with the graph for it (except for LASSO Logistic Regression- only score no graph)
## One limitation/risk
The response variable "left_flag" is unbalanced in the data (about a quarter churned) so the training and test splits may be unbalanced as well
