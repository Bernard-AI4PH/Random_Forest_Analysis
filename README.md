# Random Forest Analysis

Random Forest analysis for diabetes prediction ,including SMOTE balancing, hyperparameter tunning and model evaluatio

# Objectives 

The following objectives were achieved in the assignment, to:

1. Develop proficiency in implementing Random Forest algorithms for predictive analysis.
2. Understand the importance of hyperparameter tuning and its impact on model performance.
3. Gain experience in comparing models to select the best-performing configuration.
4. Learn to interpret Random Forest results, including feature importance



# Dataset

The [Can Path Student Dataset](https://canpath.ca/student-dataset/) was used  to perform a Random Forest Analysis. The dataset has already been cleaned using [Multivariate Imputation by Chained Equations](https://www.rdocumentation.org/packages/mice/versions/3.17.0/topics/mice) method to handle missing data. 

The data has 41187 observation and 93 columns after cleaning. 


# Description of project 

This project implements a [Random Forest](https://parsnip.tidymodels.org/reference/rand_forest.html) analysis, model to predict diabetes based on various health-related predictors. It begins by loading the necessary libraries and reading in the dataset. The diabetes variable is then recoded into a binary outcome for classification. Initial exploratory data analysis reveals an imbalance in the predictor variable, with a significantly lower proportion of "Yes" responses. To address this, SMOTE (Synthetic Minority Over-sampling Technique) is applied to balance the dataset.

The dataset is split into training (70%) and testing (30%) subsets, ensuring stratified sampling based on the diabetes variable. A baseline Random Forest model is trained using default hyperparameters. The model's performance is evaluated using accuracy, sensitivity, specificity, precision, and F1-score. The ROC curve is generated to assess classification performance.

To improve the model, hyperparameter tuning is performed using grid search and cross-validation. The best-performing parameters are selected, and the final optimized model is trained. Predictions are made on the test set, and model metrics are compared between the default and tuned models. Additionally, feature importance analysis is conducted using permutation-based methods. Finally, various performance metrics, including ROC curves, accuracy, and precision comparisons**, are visualized to demonstrate the impact of tuning on model performance.


# Files attached to repository

There are 2 files attached to this repository. TWO rmarkdown files and their respective html outputs.

1.  The [Bernard_Asante_CHEP_898_Random_Forest_DM.Rmd](https://github.com/Bernard-AI4PH/Random_Forest_Analysis/blob/main/Bernard_Asante_CHEP_898_Random_Forest_DM.Rmd) file is the [RMarkdown](https://rmarkdown.rstudio.com/) that implements a Random Forest model to predict diabetes. It includes data preprocessing, exploratory data analysis, handling class imbalance with SMOTE, model training with hyperparameter tuning, performance evaluation using accuracy, sensitivity, and precision, and model comparison through ROC curves and feature importance analysis.


2. The [Bernard_Asante_CHEP_898_Random_Forest_DM.html](https://github.com/Bernard-AI4PH/Random_Forest_Analysis/blob/main/Bernard_Asante_CHEP_898_Random_Forest_DM.html) file is the html output of the R markdown file. This file can be downloaded and view in the web browser. 
