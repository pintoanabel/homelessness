# homelessness
The purpose of this repository is to explore the relationships between housing market factors and homelessness in the Seattle King County Area.

# Data
The dataset comes from the U.S. Department of Housing and Urban Development (HUD), which contains various housing market factors as well as homelessness data.
Link to the report regarding the HUD dataset: https://www.huduser.gov/portal/sites/default/files/pdf/Market-Predictors-of-Homelessness.pdf
Link to the dataset in this repository (before data cleaning): https://raw.githubusercontent.com/pintoanabel/homelessness/main/05b_analysis_file_update.csv

## Requirements
No installed software was used for this project. Google Colab was utilized as the host environment for Python, which requires no software installation.

## Data Preparation
a subset of the data was taken to include only variables that we were interested in seeing their relationship to homelessness
missing values were removed from the data
variables were renamed to have informative names
total demographic counts were converted to rates

the notebook where the data was cleaned can be found in this repo: https://github.com/pintoanabel/homelessness/blob/main/Pinto_Prep_Homelessness_Data_Preparation.ipynb

## Data Analysis
a train test split was generated, regression models of the all the selected predictors were generated, Lasso and ridge regressions for the full model were generated as well, in addition to an XGBoost model. Data on city/urba, suburban, and rural areas were added back in, and lasso regressions were run.

The notebook in this repo that contains the steps for data analysis can be found here: https://github.com/pintoanabel/homelessness/blob/main/Pinto_Analysis_Homelessness_Analysis_Template.ipynb

## Authors
The author of this repository and its contents is Anabel Pinto LinkedIn: https://www.linkedin.com/in/anabel-pinto/

## License
GNU GPLv3 (GNU General Public License v3.0)
