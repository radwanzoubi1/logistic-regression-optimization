# Logistic Regression Optimization

This project implements logistic regression from scratch and optimizes it for multi-class classification tasks using the Obesity Dataset. The primary goal is to predict obesity levels and compare the custom implementation's performance against scikit-learn’s built-in logistic regression model. Additionally, the project explores advanced optimization techniques, regularization methods, and performance evaluation to provide insights into logistic regression's applicability and effectiveness in real-world scenarios.

---

## About the Dataset

### Domain:
- **Obesity**: A global health crisis affecting over 2 billion people worldwide, linked to chronic conditions such as diabetes, cardiovascular issues, and certain cancers.
- **Purpose**: This dataset highlights key factors like eating habits, physical activity, and psychological influences to enable predictive modeling and offer actionable insights for prevention and intervention strategies.

### Dataset Overview:
- **Data Type**: Tabular data with numeric and categorical variables.
- **Task**: Multi-class classification.
- **Attributes**:
  - Numeric features: Includes values like age, height, and weight.
  - Categorical features: One-hot encoded variables such as dietary habits and activity levels.
- **Class Variable**: Obesity levels categorized into Underweight, Normal, Overweight, and Obesity.
---
## Project Objectives

1. **Custom Logistic Regression Implementation**:
   - Built using NumPy and SciPy with a focus on:
     - One-vs-All (OvA) classification.
     - Optimization techniques: steepest ascent, stochastic gradient ascent, and quasi-Newton methods.
     - Regularization options: L1, L2, and elastic net.

2. **Comparative Analysis**:
   - Benchmarked the custom implementation against scikit-learn’s logistic regression.
   - Evaluated performance in terms of training time, accuracy, and generalization.

3. **Parameter Tuning**:
   - Investigated the impact of regularization strength (`C`) and solver choices.

4. **Visualization**:
   - Visualized performance differences using graphs and charts.

---

## Key Questions Explored

1. **What is the impact of regularization on model performance?**
   - Explored using accuracy scores and validation plots.

2. **Which optimization technique provides the best performance?**
   - Compared training times and convergence behaviors.

3. **How does the custom model compare to scikit-learn's implementation?**
   - Analyzed differences in accuracy, scalability, and computational efficiency.

---

### Data Preprocessing:
1. **Scaling**: Standardized numeric features to improve model performance.
2. **Encoding**: Applied one-hot encoding to categorical variables.
3. **Splitting**: Dataset divided into 80% training and 20% testing data for model validation.

---
## Results

1. **Custom Implementation**:
   - Demonstrated competitive accuracy with scikit-learn’s logistic regression.
   - Quasi-Newton methods achieved the fastest convergence.
   - Regularization improved generalization and reduced overfitting.
2. **Comparison**:
   - scikit-learn’s implementation was faster and more efficient for deployment.
   - Custom implementation provided greater flexibility and insight into optimization.
---

## Tools and Libraries Used

- **Python**: Programming language.
- **Jupyter Notebook**: Interactive coding environment.
- **NumPy**: Numerical operations.
- **SciPy**: Optimization routines.
- **scikit-learn**: Benchmark logistic regression.
- **Pandas**: Data manipulation.
- **Matplotlib**: Data visualization.

---
### Data Source:

- Obesity Dataset:
https://www.kaggle.com/datasets/suleymansulak/obesity-dataset
---

## Project Structure

```plaintext
.
├── Logistic-Regression-Optimization.ipynb   # Main Jupyter Notebook
├── dataset.csv                              # Dataset used for analysis
├── README.md                                # Project documentation
```

---

## How to Run

### 1. Clone the Repository:
```bash
git clone https://github.com/logistic-regression-optimization/logistic-regression-optimization.git
cd logistic-regression-optimization
```

### 2. Install Dependencies:
```bash
pip install numpy scipy pandas matplotlib scikit-learn
```

### 3. Run the Notebook:
- **Open Jupyter Notebook**:
```bash
jupyter notebook Logistic-Regression-Optimization.ipynb
```
- Run all cells to reproduce the analysis.







