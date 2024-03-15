# Sentiment Analysis With Python's NLTK Library
## Overview
Using NLTK's Pre Trained Sentiment Analyzer: VADER, This project aims to determine the sentiments behind a review and assign a value to them based on how positive or negative the review is. Using this information we can analyze the overall public opinion of the business, and look into ways it can be improved.

## Requirements
This project was developed using Jupyter Notebook. To execute the notebook, please install Jupyter Notebook first.
```
pip install notebook
```
You can install the other dependencies by running:
```
pip install -r requirements.txt
```
<a href="https://www.kaggle.com/datasets/d4rklucif3r/restaurant-reviews?rvi=1">The dataset is included in this repository but can also be found here</a>

## Test Results
This project uses data from an Excel Workbook called "reviews.xlsx", and generates a csv file containing each review with their sentiment polarity. A negative value for sentiment polarity indicates a negative review, whereas a positive value indicates a positive review.
<p align="center">
<img src="https://github.com/MJHendricks/sentiment-analysis/assets/65013192/7c1eab82-7101-4494-90df-12c522355001" height="400px", width= "500px">
</p>


According to the Analyzer, The resturant seems to have 66% positive reviews. The Sentiment Analyzer determined that the following was the most positive review, with a sentiment polarity of 1.0 (the highest posible value):

- "DELICIOUS!!"

Whereas within the 34% negative reviews, the review determined to be the most negative, with a sentiment polarity of -0.855:

- "RUDE & INCONSIDERATE MANAGEMENT."

The most negative review is related to the management of the resturant, further investigation into mentions of management in reviews revealed the following:
- "The management is rude."
- "Terrible management."
- "We recently witnessed her poor quality of management towards other guests as well."
- "Best of luck to the rude and non-customer service focused new management."
- "I have watched their prices inflate, portions get smaller and management attitudes grow rapidly!"

There seems to have been a recent change in management, which has resulted in unhappy customer reviews. Further training of the new management may be needed to secure a more positive public opinion.

## Conclusion
VADER definitely needs more work, as it marked a number of reviews incorrectly as negative or positive. However it is useful for a looking for patterns in reviews, as we did above by looking into reviews containing the word "management", as well as getting a general overview of the public opinion of the establishment.
