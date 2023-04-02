Drug-Review-Classification

ML Project 

Mahesh Nyalam, Akash Ghanta

In order to categorize the effectiveness of a given drug for a given condition based on thousands of user evaluations from drugs.com, the project used machine learning models and various Python libraries (pandas, numpy, matplotlib, nltk, sklearn).

The dataset, which has 215,000 rows and 6 characteristics, was obtained from the UCI Drug Review Dataset. (drug name, condition, date, review, rating, useful count).

All of the project's code is available in the Jupyter notebooks:

Cleaning - Data loading, early data exploration, data cleaning and filtering (including the use of nltk sentiment analysis on reviews), and pre-processing the filtered dataset are all covered by the cleaning code. Four cleansed and prepared csv files that can be used in the second notebook are the output of this notebook.

Models - contains all 6 models used in this study, as well as code for dividing the pre-processed data into training and testing sets and standardizing the train and test data. Last but not least, it has visualizations of the findings and analysis, along with metrics for evaluating each model.

For access to drugs_clean.csv to load in to the cleaning notebook, click the below link for a shareable google drive file:

https://drive.google.com/file/d/1oczqQdNmKpjXpzi4ZjZOOem9JlRXmZAk/view