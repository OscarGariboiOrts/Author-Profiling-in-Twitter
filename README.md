# Author-Profiling-in-Twitter
This repository compounds the basic work done under the subject Text mining in Social Media at Big Data Analytics Master Course (UPV)

The objective of the task is to build a classifier for Tweets written in Spanish language. There are two characteristics to be classified, Variety and Gender. Variety corresponds to the spanish language used in 7 different countries (Spain, México, Venezuela, Perú, Colombia, Argentina and Chile), while Gender, obviously, corresponds to the fact that the author is male or female. One or more jobs have been built to predict both characteristics and for that we have some tools to work with.

Dataset: We've been provided with a dataset composed by 100 tweets for 2800 authors as Train Data. We've also been provided with 100 tweets for 1400 authors as Test Data.

We'll split the classification problem into 2 smaller problems and approaches, one for Variety classification (7 classes) and another for Gender classification (2 classes).

We have performed some data mining to the datasets: Part Of Speech-Tagging, Twitter specific features counting, and some other. 

We'll show 2 different note-books with the 2 different approaches we have followed for each sub-problem: Author Profiling in Twitter - Variety Prediction.ipynb and Author Profiling in Twitter - Gender Prediction.ipynb.

A Baseline based on a Bag-of-Words was provided. The main goal of this tasks, besides the pure pleasure of learning, has been set in beating the Baseline.

A basic code written in R was provided by the instructors. This basic code basically implemented the Bag-of-Words approach. Completely new code has been written using Python. Tweets both in train and test datasets have been preprocessed to remove the accents.

There has been a testing phase where 82 different models have been built and tested. Finally the models with best performance were selected and reported in the attached note-book files.

Further information about the tasks done under the scope of Variety and Gender classification can be found in the corresponding sections (story telling).

A paper was also written in order to formally present the work done and the results that this work showed.
