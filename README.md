# Web-scraping-and-text-review-classifiation-using-python.
The objective of this task is to scrape consumer reviews from a set of web pages and evaluate the performance of text classification on the data. The reviews have been divided into five categories here:
http://mlg.ucd.ie/modules/yalp

Each review has a star rating. For this assignment, we will assume that 1-star to 3-star reviews are “negative”, and 4-star to 5-star reviews as “positive”.

# Tasks: 

1. Select two review categories of your choice. Scrape all reviews for each category
  and store them as two separate datasets. For each review, you should store the
  review text and a class label (i.e. whether the review is “positive” or “negative”).
2. For both category datasets:
  a. From the reviews in this category, apply appropriate preprocessing steps to
     create a numeric representation of the data, suitable for classification.
  b. Build a classification model using a classifier of your choice, to distinguish
     between “positive” and “negative” reviews.
  c. Test the predictions of the classification model using an appropriate
     evaluation strategy. Report and discuss the evaluation results in your
     notebook.
3. Evaluate how well your two classification models transfer between category.
   That is, run experiments to:
   a. Train a classification model on the data from “Category A”, and evaluate its
      performance on the data from “Category B”.
   b. Train a classification model on the data from “Category B”, and evaluate its
      performance on the data from “Category A”. 
