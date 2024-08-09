# Heart Disease Dataset Analysis

## Introduction
This repository contains an in-depth analysis of a heart disease dataset sourced from Kaggle. The project aims to explore and understand the data by applying statistical measures, visualizations, and interpreting the relationships between different variables. The analysis is structured to provide insights into the factors that may contribute to heart disease.

## Dataset Information
- **Dataset Name**: Heart Disease Dataset
- **Source**: [Kaggle - Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- **Description**: The dataset includes medical information about patients, such as age, gender, blood pressure, cholesterol levels, and more, which are potentially related to heart disease.

## Repository Structure

### 1. `heart.csv`
- **Description**: The original dataset obtained from Kaggle. This CSV file includes multiple features such as age, sex, chest pain type, resting blood pressure, serum cholesterol, and target (indicating the presence of heart disease).
- **Usage**: This file serves as the raw data input for the analysis.

### 2. `heart.xlsx`
- **Description**: An Excel file that extends the raw dataset by providing:
  - **Variable Sheets**: Separate sheets for each of the 14 variables, including:
    - **Visualizations**: Charts and graphs representing the distribution and behavior of each variable.
    - **Calculations**: Statistical calculations such as mean, median, mode, variance, standard deviation, and interquartile range (IQR).
    - **Interpretations**: Detailed interpretations of the statistical results to provide insights into the data.
- **Purpose**: To offer a comprehensive view of each variable's role in the dataset and its potential impact on heart disease.

### 3. `Activity_Analysis_Solution_By_Gajendra_Singh.xlsx`
- **Description**: This Excel file contains two main analytical sheets:
  - **Sheet 1: Measures of Central Tendency and Dispersion**
    - **Columns**:
      - `Variable Name`: Name of the variable extracted from the dataset.
      - `Measure of Central Tendency`: The most suitable measure (mean, median, or mode) selected based on the data distribution.
      - `Reason for Central Tendency`: Explanation for the chosen measure of central tendency.
      - `Measure of Dispersion`: Calculation of range, variance, standard deviation, IQR, etc.
      - `Reason for Dispersion`: Justification for the selected measure of dispersion.
      - `Reference`: Pointer to the corresponding sheet in `heart.xlsx` for more detailed analysis.
  - **Sheet 2: Association Between Variables**
    - **Columns**:
      - `Variable 1`: First variable involved in the association analysis.
      - `Variable 2`: Second variable involved in the association analysis.
      - `Association Between Variables`: Detailed analysis of the relationship between the variables, using methods such as:
        - Contingency tables for categorical variables.
        - Scatter plots for numerical variables.
        - Covariance and correlation coefficients for numerical variables.
    - **Rows**: Includes analysis of associations between selected categorical and numerical variables as per the course requirements.

## Analytical Insights

### Central Tendency and Dispersion
- **Objective**: To summarize the data using appropriate measures of central tendency (mean, median, mode) and dispersion (range, variance, standard deviation, IQR).
- **Methodology**:
  - Each variable was analyzed individually, and the most suitable statistical measures were selected based on the nature of the data.
  - Detailed reasons for the selection of each measure are documented to ensure clarity and transparency.
- **Outcome**: The analysis provides a clear understanding of the distribution and variability of each variable, which helps in identifying key factors that may influence heart disease.

### Association Between Variables
- **Objective**: To explore relationships between selected variables in the dataset.
- **Methodology**:
  - Associations between categorical variables were examined using contingency tables and visualized with 100% stacked bar charts.
  - Relationships between numerical variables were analyzed using scatter plots, covariance, and correlation coefficients.
  - Insights were drawn from the observed patterns and statistical results.
- **Outcome**: The analysis reveals important connections between variables, offering potential explanations for how they may contribute to heart disease.

## How to Access and Use the Files
- **heart.csv**: Use this file to explore the raw data and understand the structure of the dataset.
- **heart.xlsx**: Review this file to see detailed visualizations, calculations, and interpretations for each variable.
- **Activity_Analysis_Solution_By_Gajendra_Singh.xlsx**: Refer to this file for a summary of the statistical analysis, including measures of central tendency, dispersion, and associations between variables.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact Information
For further information, questions, or collaboration opportunities, please contact me via [email](mailto:bswgajendra@gmail.com).

