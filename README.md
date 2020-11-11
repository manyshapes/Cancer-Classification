# Breast-Cancer-Classification

# Intent
Seer Database has kept a record of breast cancer cases from 1975 to 2017. Breast cancer morbidity cases make up ~17% of the observations in the database. Apart from skin cancers, breast cancer is the most common cancer in the United States. With morbidity being a real possibility in those diagnosed with breast cancer, quantifying the likelihood of it occuring is a useful metric for patients, their families, and health care teams to assess options and possible trajectories.

Using supervised Ensemble classification, machine learning is able to offer morbidity predictions. These predictions are imperfect & not always accurate, but can act as supplemental information for those on a health care journey or alongside someone else's. Note these predictions are not be taken in place of trained medical advice and are solely available for research purposes.


# In the Repo

### Workflow
The steps taken for this classification were performed in a series of work/notebooks. Note the first files are ipynb jupyter files while the last is a Tableau workbook.

1. Acquiring Data: *Data Retrieval.ipynb*
2. Data Processing: *Data Processing.ipynb*
3. Tuning and Modeling: *Classification Modeling.ipynb*
4. Visualizing Predictions: *predsbook.twb*

## Visualizations Included in folder:
1. Ages and Predictions.png: a view of how average probabilities change throughout ages
2. Counts Across Stages.png: showing relative number of observations across cancer stages
3. Months Survival: trend in average probabilities across age groups
4. Probabilities Across Stages: similar to 2, but is colored to show the number of positive predictions in each stage

Powerpoint file MorbidityClassification is also available as .pdf

## Files included in original repo but not shared Repos:
1. 75bc.csv - initial file from SEER
2. 75edits.csv - processed file
3. bcandpreds.csv - test set with predictions in dataframe


# Tools Used
Using **Python** in **Jupyter Notebooks** , **h2o ai** was used to create models Random Forests, Naive Bayes, and XGBoost. **Pandas** dataframes were used for data handling. Visualizations were created in **Tableau**. The data was retreived using **SEER\*Stat** Software.