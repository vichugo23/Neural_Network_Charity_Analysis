# Neural_Network_Charity_Analysis

## Overview of the analysis

For this analysis we will use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. From Alphabet Soup’s business team we will use a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years.




## Results

- Data Preprocessing
  The **target variable** in this analysis is the **IS_SUCCESSFUL** column.
  The **features** for this model include:
  - **ORGANIZATION**
  - **STATUS**
  - **INCOME_AMT**
  - **SPECIAL_CONSIDERATIONS**
  - **ASK_AMT**
  - **APPLICATION_TYPE**
  - **AFFILIATION**
  - **CLASSIFICATION**
  - **USE_CASE**
  
  Only two variables, **NAME & EIN**, were seen as unnecessary and were removed.

- Compiling, Training, and Evaluating the Model
  - hidden nodes layer 1 had 80 neurons
  - hidden nodes layer 2 had 30 neurons
  - there were 43 input features used


The model produced **53.6% accuracy** which did not meet the target model performance of at least 75% accuracy. I did make a few more adjustments later on in attempt to increase the model's performance by removing other features that could've been seen as unnecessary, adjusting the number of neurons and layers. After all of these attempts I stil couldn't manage to produce a more accurate model.

#Summary 
After running a deep learning model I was only able to produce an accuracy score of **53%**. I would not recommend using this model since it is right about half the time. I would recommend using logistic regression model for this scenario.
