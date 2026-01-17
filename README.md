This notebook demonstrates a complete workflow for multiclass classification in a customer segmentation scenario. The goal is to segment customers into 4 categories (A, B, C, D) based on the following features:

Var_1 (numeric)

Spending_Score (numeric)

Profession (categorical)

Graduated (binary)

GENDER (binary)

Spending_Level (ordinal: Low/Medium/High)

Notebook Steps
1. Data Preprocessing

Handle missing values

Encode categorical features:

Nominal → One-hot encoding

Ordinal → Label encoding (Low/Medium/High → 0/1/2)

Binary → 0/1

Scale numeric features (Var_1, Spending_Score)

2. Target Preprocessing

Encode target column (A/B/C/D) using Label Encoding → 0/1/2/3

Split dataset into train/test sets (stratified to preserve class distribution)

3. Model Training
Softmax Logistic Regression (multinomial logistic regression)

Predict class labels and softmax probabilities
4. Evaluation
Accuracy
Learning Outcomes

Understand the softmax function and its application in multiclass classification


Check out the demo video: [YouTube Link]([(https://youtu.be/9CxfUWrGsW4?si=_GJTcpG458s0qUlQ)])

Learn to preprocess mixed feature types for ML models

Evaluate multiclass models using accuracy
4. Evaluation

Accuracy
