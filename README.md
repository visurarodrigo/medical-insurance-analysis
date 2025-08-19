# Medical Insurance Charges Analysis 💉

## Project Description
This project analyzes a **medical insurance dataset** and develops predictive models to estimate **insurance charges** based on demographic and health-related features. The dataset includes information such as **age, gender, BMI, number of children, smoker status, and region** of insured individuals in the USA.  

The project demonstrates **data cleaning, exploratory data analysis (EDA), and regression modeling** including:  
- Single Variable Linear Regression (BMI)  
- Multiple Linear Regression  
- Ridge Regression with hyperparameter tuning  
- Polynomial Ridge Regression for capturing non-linear patterns  

This project was completed as part of the **IBM Data Analysis with Python** course on Coursera.

## Dataset
- **Source:** [Medical Insurance Dataset – IBM Coursera / Kaggle]([https://www.kaggle.com/datasets/mirichoi0218/insurance](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DA0101EN-Coursera/medical_insurance_dataset.csv))  
- **Features:**

| Column Name      | Description                                          | Type       |
|-----------------|------------------------------------------------------|------------|
| age             | Age of the insured                                   | Integer    |
| gender          | Gender of the insured (1: Female, 2: Male)          | Categorical |
| bmi             | Body Mass Index of the insured                       | Float      |
| no_of_children  | Number of children the insured has                  | Integer    |
| smoker          | Smoker status (1: Smoker, 2: Non-smoker)           | Categorical |
| region          | Region in the USA (1: NW, 2: NE, 3: SW, 4: SE)     | Categorical |
| charges         | Insurance charges in USD                             | Float      |

## Project Structure

- insurance_analysis.ipynb
- insurance.csv
- Plots
- README.md 

## Features and Analysis
1. **Data Cleaning:**  
   - Handled missing values for numeric and categorical features.  
   - Updated data types and rounded insurance charges for clarity.  

2. **Exploratory Data Analysis (EDA):**  
   - Histograms, scatter plots, boxplots for distributions and relationships.  
   - Correlation heatmap to identify key features affecting charges.  

3. **Regression Models:**  
   - Single Variable Linear Regression (BMI)  
   - Multiple Linear Regression (all features)  
   - Ridge Regression (regularized)  
   - Polynomial Ridge Regression (degree 2)  

4. **Model Evaluation:**  
   - Metrics: **Mean Squared Error (MSE)**, **R² Score**  
   - Visual comparison of actual vs predicted charges.  

## Key Insights
- **Smoker status** is the most influential factor for insurance charges.  
- **BMI** and **age** also affect charges but less than smoking.  
- Ridge Regression with tuning provided the best predictive performance.  
- Polynomial features slightly improved predictions by capturing non-linear relationships.  

---

## How to Use This Repository
1. Clone the repository:  
2. Open the Jupyter notebook file:
3. Ensure required libraries are installed:
4. Run the notebook cells sequentially to reproduce the analysis and visualizations.

References

- IBM Data Analysis with Python – Coursera
- Kaggle: Medical Insurance Dataset (CC0 1.0 Universal License)
- Python Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Author - Visura Rodrigo


