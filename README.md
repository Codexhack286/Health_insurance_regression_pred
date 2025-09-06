# Medical Insurance Cost Prediction

A comprehensive machine learning project that predicts medical insurance costs based on personal characteristics using regression analysis.

## 📊 Project Overview

This project analyzes a medical insurance dataset to build a predictive model for insurance charges. It demonstrates a complete data science workflow from exploratory data analysis to model evaluation, making it an excellent learning resource for understanding regression analysis in healthcare applications.

## 🎯 Objectives

- Predict medical insurance costs based on personal characteristics
- Perform comprehensive exploratory data analysis (EDA)
- Build and evaluate a multiple linear regression model
- Understand the relationship between lifestyle factors and insurance costs

## 📋 Dataset

The dataset contains **1,338 insurance records** with the following features:

| Feature | Description | Type |
|---------|-------------|------|
| `age` | Age of the insured person | Numerical |
| `sex` | Gender (male/female) | Categorical |
| `bmi` | Body Mass Index | Numerical |
| `children` | Number of dependents | Numerical |
| `smoker` | Smoking status (yes/no) | Categorical |
| `region` | Geographic region (northeast, northwest, southeast, southwest) | Categorical |
| `charges` | Insurance charges (target variable) | Numerical |

## 🛠️ Technologies Used

- **Python 3.x**
- **Jupyter Notebook**
- **Libraries:**
  - `pandas` - Data manipulation and analysis
  - `numpy` - Numerical computations
  - `matplotlib` - Data visualization
  - `seaborn` - Statistical data visualization
  - `scikit-learn` - Machine learning algorithms
  - `statsmodels` - Statistical modeling

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels jupyter
```

### Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/medical-insurance-prediction.git
cd medical-insurance-prediction
```

2. Launch Jupyter Notebook:
```bash
jupyter notebook Medical_costs.ipynb
```

## 📈 Project Structure

```
medical-insurance-prediction/
│
├── README.md                 # Project documentation
├── Medical_costs.ipynb      # Main analysis notebook
├── insurance.csv           # Dataset
└── requirements.txt        # Dependencies
```

## 🔍 Analysis Workflow

### 1. Data Exploration
- **Dataset Overview**: Basic statistics and data types
- **Missing Values**: Comprehensive check for data quality
- **Distribution Analysis**: Understanding feature distributions
- **Correlation Analysis**: Identifying relationships between variables

### 2. Data Preprocessing
- **Categorical Encoding**: Converting categorical variables to numerical
- **Feature Engineering**: Creating dummy variables
- **Data Transformation**: Log transformation of skewed target variable
- **Multicollinearity Check**: Using Variance Inflation Factor (VIF)

### 3. Model Building
- **Train-Test Split**: 80/20 split for model validation
- **Linear Regression**: Implementation using scikit-learn
- **Model Training**: Fitting the model on training data

### 4. Model Evaluation
- **Performance Metrics**: R-squared score analysis
- **Residual Analysis**: Checking model assumptions
- **Prediction Visualization**: Scatter plots of predicted vs actual values
- **Statistical Validation**: OLS assumptions testing

## 📊 Key Findings

- **Smoking Status**: Strongest predictor of insurance costs
- **Age**: Positive correlation with insurance charges
- **BMI**: Higher BMI associated with increased costs
- **Model Performance**: Achieved R² score of approximately 0.76

## 🎨 Visualizations

The project includes comprehensive visualizations:
- Distribution plots for all numerical features
- Box plots for categorical vs numerical relationships
- Scatter plots for prediction accuracy assessment
- Residual plots for model validation

## 🔮 Model Performance

- **Training R² Score**: ~0.76
- **Model Type**: Multiple Linear Regression
- **Key Insights**: Smoking status is the most significant cost factor

### Skills Demonstrated:
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Statistical analysis and hypothesis testing
- Machine learning model implementation
- Data visualization techniques
- Model evaluation and validation

## 🙏 Acknowledgments

- Dataset source: [Kaggle Medical Insurance Dataset](https://www.kaggle.com/)
- Inspiration from various data science tutorials and courses
- Open source community for excellent Python libraries

---

⭐ **If you found this project helpful, please give it a star!** ⭐