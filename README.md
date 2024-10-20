# TP_Bayesian_Network

# Bayesian modelling and XGBoost for credit risk prediction

This project presents a tutorial on Bayesian modelling and machine learning for credit risk prediction using a German credit dataset. The tutorial is structured in three main parts: Bayesian modelling, causal inference and comparison with a standard machine learning model (XGBoost).

## Content

### Part 1: Bayesian modelling of credit risk
- Construction of a Bayesian network to model the relationships between variables.
- Learning the structure and conditional distributions of the network.
- Identify dependencies between variables and use the **Markov Blanket** to select the most relevant variables.

### Part 2: Bayesian inference and causal analysis
- Estimation of joint and conditional distributions using Bayesian inference.
- Analysis of the causal effects of variables (`Job`, `Duration`, etc.) on credit risk.
- Use of the **do-calculus** and calculation of the **Average Treatment Effect (ATE)**.

### Part 3: Comparison with a machine learning model (XGBoost)
- Preparation of data (encoding of categorical variables) for **XGBoost**.
- Training and evaluation of a **XGBClassifier** model.
- Comparison of performance with the Bayesian model using accuracy and the confusion matrix.
- Training of **XGBoost** with the variables selected by the **Markov Blanket** to assess the impact of dimensionality reduction.
