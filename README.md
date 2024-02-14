# Book-Reviews-Sentiment-Analysis-with-Machine-Learning

Developed a sentiment analysis model using Natural Language Processing to classify the customer reviews into 3 polarities namely Positive, Negative and Neutral.

For Testing purposes took a similar problem of sentiment analysing hotel reviews and the dataset is obtained from Kaggle of Tripadvisor company

# Objective

Using Natural Processing Library in python, we have to develp a machine learning model so as to classify the reviews

# Prerequisites

Install following packages:

pip install numpy 
pip install pandas 
pip install sklearn 
pip install keras 
pip install seaborn
import nltk
nltk.downloader.download('vader_lexicon')

# Model Building

The Vader Lexicon dictionary 

The NLTK library already has an inbuilt sentimentanalyzer function which will take the input text

The function is directly used to compute the sentiments scores of the incoming text and to arrive at an aggregate a function is written to sum all the polarity scores

# Conclusion

Using the natural language processing library, the sentiment scores of all the texts are computed and classified all the reviews as per the polarity. The model is also deployed using Streamlit so as to use it in realtime.
