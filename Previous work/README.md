![](https://img.shields.io/github/repo-size/kiranrawat/Detecting-Fake-News-On-Social-Media)

## Fake News Detection on Social Media:

### Overview:
The easy accessibility and rapid dissemination of information through social media have resulted in the proliferation of false or misleading news. The impact of this was evident during the 2016 US presidential election, where a fake news story about Hillary Clinton allegedly commissioning the murder of an FBI agent gained significant traction on social media.

### Motivation and Background:
-The widespread dissemination of false information on social media platforms.
-With social media being the most economical means of communication, it is fascinating to examine how people react to popular news stories while also detecting and eliminating false information online. This is why developing a news monitoring system that focuses on news content to notify the public about fake news is crucial.


### Goals:

- Providing guidance to individuals to help them think critically about false information.
- Detecting fake news shared on social media platforms.
- Creating a classifier that can determine whether news is real or fake.
### Dataset used

https://arxiv.org/abs/1705.00648 [cs.CL]

### Data Science Pipeline:

- Data Collection : Balanced dataset collected from politifact.
- Data Preprocess: Data Clean and Natural Language Process
- EDA and Feature Selection : Binary, CountVectorizer, TFIDF
- Model Selection : Naive Bayes, Logistics Regression, SVM, BERT
- Model Training  : Scikit-Learn
- Inference : F1-Score and Confusion matrix to make an inference
- Model Deployment : Deployment on AWS or heroku
- Data Product : Flask-based web application


### Train the best model

-First we execute the cleaning.py which helps in preprocessing and cleaning the data by removing unwanted words
-Next we run the training model which contains various model selection such as Naive Bayes,Logistics Regression, SVM, BERT
- We run `python training.py` for finding the accuracy


