# House Prices: Advanced Regression Techniques

## Table of Content 
[Project Overview](#project-overview)

[Exploratory Data Analysis](Exploratory-Data-Analysis)

[Feature Engineering](Feature-Engineering)

[Feature Selection](Feature-Selection)

[Requirement](Requirement)

[Installation](Installation)

[Usage](Usage)

[Contributing](Contributing)

[License](License)


### Project Overview
This project is part of the Kaggle competition House Prices: Advanced Regression Techniques, where the goal is to predict house prices using various advanced regression techniques. 

Dataset to download from the below link:
https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

### Exploratory Data Analysis 
In data Analysis I analyze to find out the below stuff:
1. Missing values
2. All the numerical variables
3. Distribution of numerical variables
4. Categorical variables
5. Cadinality of categorical variables
6. Outliers
7. Relationship between independent and dependent feature(SalePrice)

### Feature Engineering
I perform all the below steps in feature Enigneering
1. Missing values
2. Temporal variables
3. Categorical variables: remove and tables
4. Standarise the values of the variables to the same range

### Feature Selection
In this feature selection phase, you performed the following:
1. Handled missing values using mean imputation to ensure that the dataset is complete.
2. Applied Lasso regression to select important features based on their coefficients, effectively filtering out less relevant features.
3. Provided insights by printing statistics on the total features, selected features, and those that were eliminated, which helps in understanding the effectiveness of the selection process.
4. Updated the dataset to include only the most relevant features for model building, improving model performance and interpretability.

### Requirement 
To run this project, you need the following packages:

  ```pip install numpy pandas matplotlib scipy scikit-learn seaborn```

### Installation
Clone the repository:

```git clone https://github.com/MichaelOdons/House-Price-Advanced-Regression-Technique.git```
```cd House-Price-Advanced-Regression-Technique```

### Usage 
To run data analysis and feature engineering notebooks:

```jupyter notebook data_analysis.ipynb```

### Contributing 
Contributions are welcome, feel free to open a pull request for improvements or additional features.

### License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
