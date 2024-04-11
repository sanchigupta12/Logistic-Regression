# GLM and Logistic Regression

## Author
Sanchi Gupta

## Date
2024-01-28

## Introduction
This project delves into the distinguishing factors between private and public institutions using the College dataset from the ISLR library. Through exploratory data analysis, logistic regression modeling, and performance evaluation, the study aims to model the probability of a college being private and evaluate the influencing factors.

## File Structure
- `logistic_regression.rmd`: R Markdown document containing the analysis process, including data exploration, logistic regression modeling, and evaluation.
- `report.html`: The HTML report generated from the R Markdown file, detailing the analysis results and interpretations.
- `README.md`: This file, providing an overview of the project and its structure.

## Dependencies
- R and RStudio
- R packages: `ISLR`, `caret`, `ggplot2`, `pROC`, `corrplot`, `knitr`, `kableExtra`, `dplyr`

## How to Run
1. Ensure that R, RStudio, and all necessary packages are installed.
2. Clone or download this repository to your local machine.
3. Open `logistic_regression.rmd` in RStudio.
4. Run the R Markdown file to conduct the analysis and generate report on the findings.

## Overview of Analysis
1. Descriptive statistics and visualizations are employed to understand the dataset's characteristics.
2. The dataset is split into training and testing sets for model validation.
3. Logistic regression is used to model the probability of a college being private.
4. Performance metrics like accuracy, precision, recall, specificity, and AUC are calculated to evaluate the model's predictive capability.
5. ROC curves are plotted to visualize model performance.

## Conclusion
The analysis provides in-depth insights into the attributes differentiating private and public colleges. The logistic regression model shows a high level of predictive performance, as indicated by the model evaluation metrics. The results underscore the critical role of factors like out-of-state tuition and full-time undergraduate numbers in defining a college's status.

## References
- OpenAI's ChatGPT and educational resources from Northeastern University were consulted for methodology and theoretical understanding.
