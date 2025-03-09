# Random Forest Analysis


## Description 

This assignment focuses on developing understanding and application of Random Forest
algorithms. The [Can Path Student Dataset](https://canpath.ca/student-dataset/) was used  to perform a [Random Forest](https://parsnip.tidymodels.org/reference/rand_forest.html) analysis,
conduct detailed hyperparameter tuning, and compare the performance of tuned model with  model that used default parameters. This exercise emphasizes building robust models and evaluating their performance critically.

The dataset has already been cleaned using [Multivariate Imputation by Chained Equations](https://www.rdocumentation.org/packages/mice/versions/3.17.0/topics/mice) method to handle missing data. 

# Objectives 

The following objectives were achieved in the assignment, to:

1. Develop proficiency in implementing Random Forest algorithms for predictive analysis.
2. Understand the importance of hyperparameter tuning and its impact on model performance.
3. Gain experience in comparing models to select the best-performing configuration.
4. Learn to interpret Random Forest results, including feature importance


# Files attached to repository

There are 4 files attached to this repository. TWO rmarkdown files and their respective html outputs.

1.  The [Bernard_Asante_CHEP_898_Random_Forest_DM.Rmd](https://github.com/Bernard-AI4PH/Random_Forest_Analysis/blob/main/Bernard_Asante_CHEP_898_Random_Forest_DM.Rmd) file is the [RMarkdown](https://rmarkdown.rstudio.com/) output containing 
code scripts on RF models to predict diabetes dichotomous predictor from  the [can_path_dataset](https://canpath.ca/student-dataset/). The feature engineering process, building default and tuned models, model prediction and evaluation has been clearly 
outline in the document.   The .rmd file was knitted to [data_wrangling_viz.html](https://github.com/Bernard-AI4PH/Random_Forest_Analysis/blob/main/Bernard_Asante_CHEP_898_Random_Forest_gen_health.Rmd) which presents the code and output in a single file.
This file can be downloaded and viewed on a web browser 


2. The [Bernard_Asante_CHEP_898_Random_Forest_gen_health.Rmd](https://github.com/Bernard-AI4PH/Random_Forest_Analysis/blob/main/Bernard_Asante_CHEP_898_Random_Forest_gen_health.Rmd) also applied RF model on the can path student dataset using gen health as a predictor.
The HS_GEN_STATUS was recoded into poor, good and excellent. Data processing, data visualization, feature engineering and steps for building the machine learning model has been outlined in the code script.

