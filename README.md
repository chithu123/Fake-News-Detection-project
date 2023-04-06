# Fake-News-Detection-project
This repository contains code for a Fake News Detection project. The project uses machine learning techniques to analyze news articles and classify them as either real or fake. 

Fake News Detection With 99% Accuracy:
    
Objectives

To build a model that will be able to determine if an article is fake news or not.

Data Understanding

The data was obtained from kaggle Fake and real news dataset. 
There are two sets of data, both saved in CSV format. One dataset contains real news, 
while the other dataset contains false news.


Data Preparation

In this section, i am going to do the following tasks using Python and NLP libraries:

Check for duplicate values in the data and remove them if any are found.
Combine two datasets into one.
Dropping columns not to be used.
Remove all punctuations.
Convert all the text to lower case.
Create a word cloud.
Remove stopwords from the combined dataset.
Lemmatize the text data.
Split the data into training and testing set.
Tokenize the text data.

####  python -m spacy download en_core_web_sm  

### if we not install --error will come- so  the 'en_core_web_sm' model is not installed in your spaCy library. 
###You can try installing it by running the following command in your terminal or Anaconda prompt:  python -m spacy download en_core_web_sm 

Conclusion

In conclusion, the model is highly accurate and performs very well on the data it was trained and tested on.
It can predict outcomes with 99% accuracy and has high recall and precision scores, 
indicating its ability to identify relevant results and minimize incorrect results.
