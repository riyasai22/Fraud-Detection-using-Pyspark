# Fraud-Detection-using-Pyspark

### Dataset:
The PaySim dataset is a synthetic dataset that simulates mobile money transactions. The dataset contains over 6 million transactions, with information on the sender, receiver, amount, and other attributes.

### Problem Statement: 
Given a set of mobile money transactions, the goal is to develop a machine learning model that can accurately identify fraudulent transactions and prevent financial losses.

### Methodolgy:
- Data Exploration
- Feature Selection - type, amount, oldbalanceOrg, newbalanceOrig, isFraud
- Train Test Split - randomsplit 70:30
- One-Hot Encoding Categorical features
- Vector Assembler 
- Pipelining for preprocessing
- Model Training - Logistic Regression
- Performance Metrics: Recall, Precision and AOC Curve
