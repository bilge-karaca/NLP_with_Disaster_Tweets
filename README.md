# Natural Language Processing with Disaster Tweets

The aim of this project is to predict which tweets are about real disasters and which ones are not.

For this project I use the following methods: 

- Bag of words (**CountVectorizer, TfidfTransformer** etc.)
- **Defining a custom tokenizer** that also includes **lemmatization**. As an alternative, nltk's TweetTokenizer.
- Classification Method 1: **Multinomial Naive Bayes**
- Classification Method 2: **Linear Discriminant Analysis (LDA)**
- **TruncatedSVD** along with LDA to avoid potential dimensionality problems
- **Optimal hyperparameter search** through **GridSearchCV** for LDA


Link to Kaggle competition: Addison Howard, devrishi, Phil Culliton, Yufeng Guo. (2019). Natural Language Processing with Disaster Tweets. Kaggle. https://kaggle.com/competitions/nlp-getting-started
