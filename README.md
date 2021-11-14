# Building Classifiers of Specific Text Entities

The following project analyzes text classifiers that parse through 730 articles on Business Insider and extracts entities in which it recognizes as one of three given types: **CEOs, companies, and percentages.** 

Based on provided label values for each of the three categories, a logistic regression model for each entity type was constructed to classify the words based the context of the sentence they are in. The CEO classifier, company classifier, and the percentage classifier models were run through a subset of entities from the corpus composing of all 730 articles. 

The goal of this project was to extract the following:
1.	All names of CEOs in the corpus
2.	All company names in the corpus
3.	All entities involving percentages

The system parsed through a corpus of .txt files of total 730 Business Insider articles, taken from 2013 and 2014. The script is tailored to the format of these text files and will need to be adjusted if other articles are used. 

Overview and summary of the results is available in [here](https://nbviewer.org/github/yunhwanchoi/BI-Text-Classification/blob/main/Text%20Classification%20Overview.ipynb).

Full walk through of the code is available in [here](https://nbviewer.org/github/yunhwanchoi/BI-Text-Classification/blob/main/Text%20Classification%20Code.ipynb). 
