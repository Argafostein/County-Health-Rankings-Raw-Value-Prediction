# County Health Rankings – Raw Value Prediction

## About the Project

This project focuses on predicting **Raw Value** using the County Health Rankings dataset, specifically for the *Adult Obesity* measure.

The main objective is to explore the dataset, perform data preprocessing, and develop machine learning regression models to estimate Raw Value based on available county-level features.

This project also explores different preprocessing techniques and compares model performance to identify an effective regression approach.

## Objectives

- Understand and explore the County Health Rankings dataset.
- Perform Exploratory Data Analysis (EDA).
- Handle missing values and potential outliers.
- Apply feature encoding and data preprocessing techniques.
- Build machine learning regression models.
- Evaluate and compare model performance.

## Dataset

The dataset used in this project is the **County Health Rankings dataset**.

The target variable is:

- `Raw value`: The actual reported value for a particular health measure.

The project focuses on the `Adult obesity` measure.

### Features

The features used in the model include:

| Feature | Description |
|---|---|
| State | Name of the state |
| County | Name of the county |
| State code | State identification code |
| County code | County identification code |
| Year span | Period associated with the observation |
| Data Release Year | Year the data was released |
| fipscode | Federal Information Processing Standards code |

## Project Workflow

### 1. Data Understanding
- Load and inspect the dataset.
- Understand the structure and data types.
- Identify the target variable and relevant features.

### 2. Exploratory Data Analysis (EDA)
- Analyze feature distributions.
- Examine missing values.
- Explore relationships between features and the target variable.
- Identify potential outliers.

### 3. Data Preprocessing
- Handle missing values using `SimpleImputer`.
- Apply `OneHotEncoder` to categorical features.
- Separate numerical and categorical features using `ColumnTransformer`.
- Use `Pipeline` to combine preprocessing steps and machine learning models.

### 4. Model Development

The following regression algorithms are explored:

- Random Forest Regressor
- Linear Regression
- XGBoost Regressor

### 5. Model Evaluation

Model performance is evaluated using:

- **Mean Absolute Error (MAE):** Measures the average absolute difference between actual and predicted values.
- **Cross-Validation:** Evaluates model performance across multiple data splits to obtain a more reliable performance estimate.

## Technologies & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

## Repository Structure

```text
County-Health-Rankings-Raw-Value-Prediction/
│
├── data/
│   └── dataset.csv
│
├── notebooks/
│   └── raw_value_prediction.ipynb
│
├── README.md
└── requirements.txt
```

*Note: The repository structure may vary depending on the actual files uploaded.*

## Key Learning Outcomes

Through this project, I explored and practiced:

- Data cleaning and preprocessing.
- Handling missing values and categorical features.
- Feature encoding techniques.
- Building preprocessing pipelines using Scikit-learn.
- Applying regression algorithms.
- Using cross-validation for model evaluation.
- Comparing machine learning models using MAE.

## Future Improvements

- Explore additional feature engineering techniques.
- Experiment with alternative encoding methods.
- Perform hyperparameter tuning.
- Investigate additional regression algorithms.
- Improve model performance and generalization.

---

**Project Category:** Data Science & Machine Learning  
**Task:** Regression – Raw Value Prediction  
**Target Measure:** Adult Obesity
