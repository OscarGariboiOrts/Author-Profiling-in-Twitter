# Author-Profiling-in-Twitter
This repository compounds the basic work done under the subject Text mining in Social Media at Big Data Analytics Master Course (UPV)

The objective of the task is to build a classifier for Tweets written in Spanish language. There are two characteristiques to be classified, Variety and Gender. Variety corresponds to the spanish language used in 7 different countries (Spain, México, Venezuela, Perú, Colombia, Argentina and Chile), while Gender, obviously, corresponds to the fact that the author is male or female. One or more jobs have been built to predict both characteristiques and for that we have some tools to work with.

Dataset: We've been provided with a dataset composed by 100 tweets for 2800 authors as Train Data. We've also been provided with 100 tweets for 1400 authors as Test Data.

We'll split the classification problem into 2 smaller problems and approaches, one for Variety classification (7 classes) and another for Gender classification (2 classes).

We have performed some data mining to the datasets: Part Of Speech-Tagging, Twitter specific features counting, and some other. 

We'll show 2 different note-books with the 2 different approaches we have followed for each sub-problem: Author Profiling in Twitter - Variety Prediction.ipynb and Author Profiling in Twitter - Gender Prediction.ipynb.

A Baseline based on a Bag-of-Words has been provided. The main goal of this tasks, besides the pure learning pleasure, has been set in beating the Baseline.
