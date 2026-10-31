# Adult Income Prediction

## Project Overview

This project focuses on predicting whether an individual's annual income exceeds $50,000 based on demographic and employment-related attributes.

The project applies Machine Learning techniques to analyze the Adult Census Income dataset and compare different classification models.

## Project Objectives

- Explore and analyze the dataset using data visualization techniques.
- Perform data cleaning and preprocessing.
- Build and train multiple Machine Learning classification models.
- Evaluate and compare model performance.
- Identify the most influential features affecting income prediction.

## Dataset

The project uses the **Adult Census Income Dataset**, which contains demographic and employment-related information.

The target variable is `income`, with two classes:

- `<=50K`: Income is less than or equal to $50,000.
- `>50K`: Income is greater than $50,000.

## Technologies & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Joblib
- Jupyter Notebook

## Data Preprocessing

The preprocessing stage includes:

- Handling missing values.
- Separating numerical and categorical features.
- Applying SimpleImputer for missing data.
- Applying StandardScaler to numerical features.
- Applying OneHotEncoder to categorical features.
- Preparing the target variable for classification.

## Machine Learning Models

Three classification models are implemented and compared:

1. **Logistic Regression**
2. **Random Forest Classifier**
3. **Multi-Layer Perceptron (MLP) Neural Network**

## Model Evaluation

The models are evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

## Feature Importance

Random Forest feature importance is used to identify the features that contribute most to income prediction.

## Project Structure

```text
Adult-Income-Prediction/
│
├── Adult_Income_Prediction.ipynb
├── README.md
└── requirements.txt
```

## How to Run

1. Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
```

2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Download the Adult Census Income dataset and place `adult.data` and `adult.test` in the same directory as the notebook.

4. Open the notebook:

```bash
jupyter notebook Adult_Income_Prediction.ipynb
```

5. Run all cells to reproduce the analysis, model training, and evaluation.

## Future Improvements

- Hyperparameter tuning.
- Cross-validation.
- Additional Machine Learning models.
- Improved model interpretability.
- Interactive income prediction interface.

---

**Developed as a Machine Learning project using Python.**
