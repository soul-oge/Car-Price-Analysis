# Car Data Analysis and Cleaning

## Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) and data cleaning on an automobile dataset to prepare it for machine learning applications. The dataset provides various features related to car specifications and pricing, which are analyzed to uncover patterns and insights.

## Dataset
- **File Name:** `automobile.csv`
- **Description:** Contains data about cars, including features such as make, model, year, mileage, fuel type, and price.

## Notebooks
### 1. Car Data Cleaning (`Car DataSet cleaning.ipynb`)
- **Objective:** Clean and preprocess the dataset to ensure data quality for machine learning.
- **Key Steps:**
  - Handling missing values.
  - Removing duplicates.
  - Converting data types.
  - Encoding categorical variables.
  - Normalizing or scaling numerical features.

### 2. Car Data Analysis (`Car Data Analysis.ipynb`)
- **Objective:** Perform EDA to understand the distribution, relationships, and trends in the data.
- **Key Steps:**
  - Loading and inspecting the dataset.
  - Visualizing data distributions and relationships using plots.
  - Identifying correlations between features.
  - Detecting outliers and anomalies.
  - Summarizing key insights for machine learning preparation.
  
## How to Run
1. Install necessary packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
2. Open the notebooks in Jupyter Notebook or JupyterLab.
3. Run `Car DataSet cleaning.ipynb` to clean and preprocess the data.
4. Run `Car Data Analysis.ipynb` to explore the dataset.

## Results & Insights
- EDA revealed significant correlations between features like mileage, fuel type, horsepower, engine size, highway-L/100Km and car price.
- Data cleaning resolved missing values and ensured the dataset was ready for machine learning modeling.

## Next Steps
- Apply feature engineering techniques.
- Train and evaluate machine learning models for price prediction or classification tasks.


*This project was developed as part of a machine learning preparation workflow.*

