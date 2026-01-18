# Twitter Sentiment Analysis

A machine learning project to predict the sentiment (positive or negative) of tweets using the **Sentiment140 dataset**. The project uses text preprocessing, stemming, and TF-IDF vectorization to train a **Logistic Regression model** for sentiment classification.

---

## **Overview**

This project performs sentiment analysis on Twitter data. The workflow includes:

* Loading and cleaning tweet data
* Text preprocessing (removing punctuation, converting to lowercase, removing stopwords)
* Reducing words to their root forms using stemming
* Vectorizing the text using TF-IDF
* Training a Logistic Regression model
* Evaluating the model’s accuracy
* Saving the model for future predictions

---

## **Dataset**

* Source: [Sentiment140](https://www.kaggle.com/datasets/kazanova/sentiment140)
* Size: ~1.6 million tweets
* Columns: `target`, `id`, `date`, `flag`, `user`, `text`
* Sentiment labels:

  * `0` = Negative Tweet
  * `1` = Positive Tweet (originally `4`, converted to `1`)

---

## **Preprocessing**

* Non-alphabetic characters removed
* Text converted to lowercase
* Stopwords removed
* Words reduced to their root forms using stemming

---

## **Model**

* Features: TF-IDF vectorized tweets
* Labels: Sentiment (`0` = Negative, `1` = Positive)
* Model: Logistic Regression

---

## **Evaluation**

* Training Accuracy: ~79.87%
* Testing Accuracy: ~77.67%

The model performs well at predicting the sentiment of tweets in large-scale datasets.

---

## **Usage**

The trained model can be saved and reused for predicting the sentiment of new tweets. It predicts whether a tweet is positive or negative.

---

## **License**

This project is licensed under the MIT License.

---

If you want, I can also **make it visually more attractive for GitHub** by adding a **project badge, dataset badge, and accuracy highlights** so it looks professional.

Do you want me to do that?
