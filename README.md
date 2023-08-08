# Product Review Analysis

## **Overview:**

The objective of this application is to scrape a collection of product reviews from a set of web pages, preprocess the data, and evaluate the performance of different classifiers in the context of two related text classification tasks: 

1. predicting review sentiment

2. predicting review helpfulness

The implementation and procedure explanation is split into two Jupyter Notebooks.

Task 1 is completed in the 1st notebook `Task1.ipynb`, while Tasks 2 and 3 are completed in the 2nd notebook `Task2_Task3.ipynb`.

## **Task 1. Data Collection**

1. Scrape the complete set of web pages from your personal website address:

   `http://mlg.ucd.ie/modules/python/assign2/<STUDENT_NUMBER>/`

2. From the web pages above, parse every review across all years 2016-2021. For each product review, extract the following information:

   i) The star rating of the review

   ii) The title text of the review

   iii) The main body text of the review

   iv) Review helpfulness information

3. Store the parsed review data in an appropriate format.

## **Task 2. Review Sentiment Classification**

1. Load the data from Task 1 and create a set of documents, one per review. And each document should consist of the concatenation of the review's title and body text.
2. Assign a class label ("positive" or "negative") to each review. We will assume that 1-star to 3-star reviews are "negative", and 4-star to 5-star reviews are "positive".
3. Apply preprocessing steps to create a numeric representation of the documents, suitable for classification.
4. Build two different binary classification models using two classifiers, to distinguish between "positive" and "negative" reviews
5. Compare the performance of the classification models using an appropriate evaluation strategy. Report and discuss the evaluation results.

## **Task 3. Review Helpfulness Classification**

1. Assign a class label (“helpful” or “unhelpful”) to each review from Task 2, based on its associated helpfulness information.
2. Build two different binary classification models using two classifiers, to distinguish between “helpful” and “unhelpful” reviews.
3. Compare the performance of the classification models using an appropriate evaluation strategy. 
4. Based on the evaluation results from both Tasks 2 and 3, compare and discuss the differences in performance for the two classification tasks (i.e. sentiment and helpfulness classification).

