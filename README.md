# Fake-News-Detection
using Machine Learning.

## Libraries used:
Pandas,NLTK,scikit-learn,numPy

## Methodology:
In the study carried out natural language processing (PLN) is used as a Python computational tool; This programming language uses different libraries and platforms, among them its PANDAS natural language
processing library (Python Data Analysis Library) which is an opensource library with BSD license that provides data structures and data analysis tools. Additionally, NLTK was used, which is a set of libraries
and programs oriented to natural language processing and Scikit-learn which is a specialized machine learning library for classification, regression and clustering. The three libraries mentioned above have
been designed to operate in conjunction with the other Numpy and Scipy libraries which were also included in the program. To obtain news for the study, a public data set located in a github
repository was used. It has two data sets one consist of fake news and another one is consistof real news.
So once having the dataset, the methodology consisted of three fundamental stages; the pre-processing that involved transforming the dataset from a .csv file to a Python object belonging to Pandas; a data
frame to be able to deal with it efficiently. Subsequently, for processing, the data was changed so that the first half of the data with false label and the second half with a true label were not simply what would cause
impartiality when applying the machine learning methods. Once this is done, groups of data are taken to make training and test sets with which tokenisation algorithms are executed so that the result is processed by
the Multinomial Naive Bayes algorithm of the Scikit-Learn package, Decision Tree and Logistic Regression and finally an array was made in analysis of graph to make analysis of the results obtained.

## three Supervised Learning Algorithms are used and those are:
1. Naive Bayes Classifier.
2. Logistic Regression.
3. Decision Tree.

## Conclusions
After evaluating all the three models, Decision Tree give the best
Accuracy i.e., 99.59%. I have refer from a research
Paper mentioned above and I successfully increase the accuracy as their
accuracy is less than 95%.
