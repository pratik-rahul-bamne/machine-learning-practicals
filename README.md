# Machine Learning Experiments

This repository contains a collection of Jupyter notebooks demonstrating various machine learning algorithms and techniques. Each notebook focuses on a specific experiment, implementing the concepts from scratch or using popular libraries like scikit-learn.

## Experiments

1. **ML_Exp_01.ipynb** - Simple Linear Regression  
   Manual implementation of linear regression using NumPy and Matplotlib for basic data fitting and prediction.

2. **ML_Exp_02.ipynb** - Linear Regression with scikit-learn  
   Using scikit-learn's LinearRegression to predict student marks based on study hours.

3. **ML_Exp_03.ipynb** - Multiple Linear Regression  
   Predicting final marks using multiple features: hours, attendance, and previous marks.

4. **ML_Exp_04.ipynb** - Logistic Regression (Binary Classification)  
   Predicting student pass/fail based on study hours using logistic regression.

5. **ML_Exp_05.ipynb** - Logistic Regression with Multiple Features  
   Binary classification using multiple input features.

6. **ML_Exp_06.ipynb** - Decision Tree Classifier  
   Classification on the Iris dataset using Decision Tree algorithm.

7. **ML_Exp_07.ipynb** - K-Nearest Neighbors (KNN)  
   KNN classification on the Iris dataset.

8. **ML_Exp_08.ipynb** - Support Vector Machine (SVM)  
   SVM classification for pass/fail prediction based on study hours and attendance.

9. **ML_Exp_09.ipynb** - Random Forest Classifier  
   Random Forest classification for student performance prediction.

10. **ML_Exp_10.ipynb** - K-Means Clustering  
    Unsupervised clustering of study hours and marks data.

11. **ML_Exp_11.ipynb** - Apriori Algorithm  
    Association rule mining using the Apriori algorithm on transaction data.

12. **ML_Exp_12.ipynb** - Time Series Prediction  
    Linear regression for predicting future values in a time series.

13. **ML_Exp_13.ipynb** - Naive Bayes Text Classification  
    Spam detection using Multinomial Naive Bayes on text data.

14. **ML_Exp_14.ipynb** - Cosine Similarity for Recommendations  
    User-based collaborative filtering using cosine similarity on movie ratings.

## Requirements

To run these notebooks, you'll need:

- Python 3.x
- Jupyter Notebook or JupyterLab
- Required libraries:
  - numpy
  - matplotlib
  - scikit-learn
  - pandas
  - mlxtend (for association rules)

## Installation

1. Install Python from [python.org](https://python.org)
2. Install Jupyter: `pip install jupyter`
3. Install required packages: `pip install numpy matplotlib scikit-learn pandas mlxtend`

## Usage

1. Clone or download this repository
2. Open a terminal in the project directory
3. Run `jupyter notebook` or `jupyter lab`
4. Open any `.ipynb` file and run the cells

## Notes

- Each notebook contains step-by-step implementation
- Some experiments use synthetic data for demonstration
- Real datasets like Iris are loaded from scikit-learn
- Visualizations are included where applicable

## Troubleshooting

- If you encounter import errors, ensure all required packages are installed
- For notebook execution issues, try restarting the kernel
- Make sure you're using a compatible Python version (3.6+ recommended)
