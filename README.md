# Sentiment Analysis With Python's NLTK Library
### Overview
Using NLTK's Pre Trained Sentiment Analyzer: VADER, 

### Requirements
This project was developed using Jupyter Notebook. To execute the notebook, please install Jupyter Notebook first.
```
pip install notebook
```
You can install the other dependencies by running:
```
pip install -r requirements.txt
```
<a href="https://www.kaggle.com/datasets/d4rklucif3r/restaurant-reviews?rvi=1">The dataset is included in this repository but can also be found here</a>

### Test Results
This project was tested using data from an Excel Workbook, "reviews.xlsx"

<img src="https://github.com/MJHendricks/sentiment-analysis/assets/65013192/c576e870-3b00-4da6-aabf-b888363b77dd" height="300px">

The resturant seems to have 66% positive reviews. The Sentiment Analyzer determined that the following was the most positive review, with a sentiment polarity of 1.0 (the highest posible value):
#### "DELICIOUS!!"

Whereas within the 34% negative reviews, the review determined to be the most negative, with a sentiment polarity of -0.855:
#### "RUDE & INCONSIDERATE MANAGEMENT."

There is definitely room for improvement however, as there were numerous reviews marked incorrectly. Therefore this tool would be more useful for a general overview of the sentiments behind many reviews, rather than focusing on each individually.
