TASK 9
## Dataset of Interest

**Dataset:** Audiology (Original) Dataset  
**Source:** UCI Machine Learning Repository — https://archive.ics.uci.edu/dataset/7/audiology+original

This dataset contains patient audiology test results along with a final diagnosis label 
(e.g. type or cause of hearing loss/disorder). As a Speech-Language Pathology and Audiology 
student, this dataset is directly relevant to my field of study.

**Question I want to answer:**
Can a small set of audiological test results reliably predict the type of hearing 
disorder a patient has?


TASK 13
## Capstone Project Plan

**Decision:** Extending my mini project on the UCI Audiology dataset into a fuller capstone.

**Capstone Question:** Can audiological test patterns be used to build a reliable, 
multi-class diagnostic support model for common hearing/audiology conditions?

### 3-Day Plan

**Day 1 — Data & Feature Improvements**
- Revisit data cleaning: instead of dropping missing values, try imputing them 
  (e.g. mode for categorical features) to keep more rows
- Handle class imbalance in the diagnosis column (check value counts, consider 
  grouping rare classes or using class_weight='balanced')
- Improve feature encoding and drop any redundant/low-value columns

**Day 2 — Modeling**
- Train and compare 3-4 models (Logistic Regression, Decision Tree, Random Forest, 
  and possibly KNN)
- Use cross-validation instead of a single train/test split for more reliable results
- Tune the best-performing model's hyperparameters (e.g. max_depth, n_estimators)

**Day 3 — Evaluation & Write-up**
- Generate a full classification report and confusion matrix for the final model
- Create 2-3 clear visualizations summarizing model performance and feature importance
- Write a final README section presenting the capstone: problem, approach, results, 
  and what I'd improve with more time/data
