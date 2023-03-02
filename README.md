# Autism_in_Toddlers
This repository contains a dataset from Kaggle, which is an autism screening questionnaire dataset for toddlers. This dataset is a screening questionnaire designed to identify toddlers with autism spectrum disorder (ASD) between the ages of 16-30 months.

## Dataset Overview
The dataset consists of 1054 rows and 20 columns. Each row represents a toddler and each column represents a feature. The dataset contains the following features:

- A1_Score - Answer to question 1 (0 = No, 1 = Yes)
- A2_Score - Answer to question 2 (0 = No, 1 = Yes)
- A3_Score - Answer to question 3 (0 = No, 1 = Yes)
- A4_Score - Answer to question 4 (0 = No, 1 = Yes)
- A5_Score - Answer to question 5 (0 = No, 1 = Yes)
- A6_Score - Answer to question 6 (0 = No, 1 = Yes)
- A7_Score - Answer to question 7 (0 = No, 1 = Yes)
- A8_Score - Answer to question 8 (0 = No, 1 = Yes)
- A9_Score - Answer to question 9 (0 = No, 1 = Yes)
- A10_Score - Answer to question 10 (0 = No, 1 = Yes)
- age - Age of the toddler in months
- gender - Gender of the toddler (0 = Male, 1 = Female)
- ethnicity - Ethnicity of the toddler (0 = Others, 1 = Black African, 2 = Middle Eastern, 3 = White European, 4 = South Asian, 5 = Black Caribbean, 6 = Latino, 7 = East Asian, 8 = Southeast Asian)
- jundice - Whether the toddler was born with jaundice or not (0 = No, 1 = Yes)
- austim - Whether the toddler already had autism (0 = No, 1 = Yes)
- contry_of_res - Country of residence of the toddler
- used_app_before - Whether the toddler had used a screening app before (0 = No, 1 = Yes)
- result - Screening test result (0 = No autism, 1 = Autism)

## Data Cleaning and Preparation
The data was already clean and well-organized, so there was not much cleaning required. The only thing we had to do was convert some categorical variables into dummy variables, such as gender and ethnicity. We also converted the country of residence variable into dummy variables by using one-hot encoding.

## Data Visualization
To gain insights into the data and explore the relationships between the features and the screening test result, we used several visualization techniques, including pairwise plot, box plot, and violin plot.

A pairwise plot, or scatter plot matrix, allowed us to visualize the distribution of each feature and the relationships between them. We used different colors to represent the 'No autism' and 'Autism' classes, which enabled us to identify any patterns or clusters in the data.

We also used box plots to visualize the relationship between some features and the screening test result. For example, we created a box plot of age by screening test result, which showed that toddlers with autism spectrum disorder tended to be younger than those without.

Lastly, we used violin plots to visualize the distribution of each feature by screening test result. This enabled us to see any differences or similarities in the distributions of the features between the 'No autism' and 'Autism' classes.

## Modeling
We used logistic regression to build a classification model to predict the screening test result. We split the data into training and testing sets, trained the model on the training set, and evaluated the performance on the testing set.

## Conclusion
In conclusion, this autism screening questionnaire dataset for toddlers provides a valuable resource for developing and evaluating models to identify toddlers with autism spectrum disorder. Through data cleaning and preparation, we were able to analyze the data and visualize the relationships between the features and the screening test result. Using logistic regression, we built a classification model and evaluated its performance using various evaluation metrics.

Further analysis and modeling can be done on this dataset, including using different classification algorithms and exploring feature selection techniques to improve the model's performance. The insights gained from this dataset can also inform healthcare professionals in their efforts to identify and diagnose toddlers with autism spectrum disorder.
