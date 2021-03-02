# Disaster-Tweet-Detection Web-app
Detecting Disaster Tweet whether its fake or real

### Summary

Twitter has become an important communication channel in times of emergency. The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. But, it’s not always clear whether a person’s words are actually announcing a disaster . So there is a need to detect whether a tweet is announcing a real disaster or fake to stop chaos.




| Problem | Data | Method | Libraries | Languages | Dataset-Link |
|------|----|------|--------|--------|------------|
|<mark>NLP</mark>|<mark>Text</mark>|<mark>Countvectorizer</mark>, <mark>Multinomial Naive Bayes</mark>| <mark>Python</mark>, <mark>Sklearn</mark>, <mark>nltk</mark>, <mark>pandas</mark>, <mark>seaborn</mark>, <mark>matplotlib</mark>, <mark>collections</mark>,<mark> unicode</mark>, <mark>contractions</mark>, <mark>joblib</mark>, <mark>re</mark>, <mark>wordcloud</mark>, <mark>plotly</mark>, <mark>cufflinks</mark>, <mark>mlxtend</mark>|<mark>HTML</mark>, <mark>CSS</mark>, <mark>Bootstrap</mark>, <mark>JavaScript</mark>, <mark>Python</mark>, <mark>Flask</mark>| https://www.kaggle.com/c/nlp-getting-started/data |

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](https://docs.anaconda.com/anaconda/install/) distribution of Python, which already has some of the above packages and more included.

### Code:


Training of the model is provided in <mark>Fake_disaster_tweet_ditection.ipynb</mark> and the dataset is available in <mark>train.csv</mark> file. Downloaded <mark>count.pkl</mark> and <mark>tweet.pkl</mark> files will be used for deployment. You will be required <mark>app.py</mark> Python file to run the template. Connect this repository to <mark>Heroku: Cloud Application Platform</mark> to deploy.  

### Model used:
- Multinomial Naive Bayes: The multinomial Naive Bayes classifier is suitable for classification with discrete features (e.g., word counts for text classification).

### Accuracy:
- Test accuracy: 77.9%

### Fake Disaster Tweet Detection:

![](/images/1.png)

![](/images/2.png)

![](/images/3.png)
