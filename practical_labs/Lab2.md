
# Lab 2 - Probability and Statistics

  

**Due Date**: October 8 11:59 PM EST.

  

This lab provides insight into the concept of probability and statistical measures that you could use to classify the data as spam or not spam and also clean the data by removing the outliers using measures of central tendency and dispersion.

  

*All the needed dataset files are included in the "datasets" folder.*

  

## Part A

  

Use the **Lab2_dataset.csv** provided.

### Preprocessing

  

- Load the dataset

- Use the [CountVectorizer](http://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.CountVectorizer.html) function in sklearn to transform the "text" feature to a vector representation of a predetermined size.

- Split the dataset into training and testing

  

### Model Training and Evaluation

  

- Train a Standard Naiive Bayes model on the training dataset and evaluate on the test set

- Train and evaluate also on the Gaussian and Multinomial Naiive Bayes Classifiers

- Compare between the performance of all models and comment on the reasons behind the differences seen between the three models.

  

## Part B

  

Use the **AB_NYC_2019.csv** dataset for this part.

### Tasks

- Remove outliers based on price per night for a given apartment/home.

- Demonstrate why using other techniques like mean/median/ percentile works.

  

*The task is to come up with a clean dataset that does not have outliers showcasing all the possibilities*

  
  

**Instructions**

  

1.  *Feel free to add additional Markdown elements (description/additional comments)*

2.  *Push the notebooks and HTML files of both parts to your lab-submission fork, and create a PR*