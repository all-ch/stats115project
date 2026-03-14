## Stats 115 Project: Bayesian Modeling of Gallstone Risk Using Clinical and Body Composition Data
## Contributors: Olivia Willard, YuNing Chou, Allinn Chen, Mihir Borkar
### Project Overview

This project investigates factors that may influence whether a patient has gallstones using Bayesian logistic regression. The goal of the analysis is to estimate the probability that a patient has gallstones based on clinical and body composition measurements.

Initially, the project aimed to examine whether comorbidity was an important predictor of gallstones. However, exploratory data analysis suggested that comorbidity had only a weak relationship with gallstone status in this dataset. Because of this, the focus of the project shifted toward identifying other variables that better explain the probability of gallstones.

Using exploratory analysis and model testing, we evaluated several potential predictors and ultimately fit a Bayesian logistic regression model using Vitamin D, bone mass, and CRP as predictors.

The Bayesian framework allows us to estimate the probability of gallstones, incorporate prior information, quantify uncertainty using posterior distributions and credible intervals, and evaluate model performance using posterior predictive checks and cross-validation

### Project File Structure

The analysis is organized in the "project code" direcotry under three main Quarto (.qmd) files that follow a clear workflow.

1. "01_data_cleaning.qmd": this file prepares the dataset for analysis and outputs the cleaned data as the file "cleaned_data.csv" in the data directory
2. "02_eda.qmd": this file performs exploratory data analysis (EDA) on the cleaned dataset
3. "03_modeling.qmd": this file fits and evaluates the Bayesian Logistic Regression Model

Our data is organized under the "data" directory with the raw data stored in "data.csv" and cleaned data stored in "cleaned_data.csv"

### How to Run the Code

1. Open the project using the file: "project.Rproj"

2. Open directory "project code" to view our R files

2. Run the files in the following order: "01_data_cleaning.qmd", "02_eda.qmd", "03_modeling.qmd"

3. View our presentation slides under the file "presentation_slides".qmd