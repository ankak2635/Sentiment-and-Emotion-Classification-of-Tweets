# Sentiment-and-Emotion-Classification-of-Tweets

Runs sentiment and emotion classification using 🤗 transformers models on about 25k tweets mentioning @Dell. Explores the sentiments and emotions to figure out the positives and negatives of the company's product and services.

* The sentiment classifier labels the tweets as either positive, negative and neutral
* The emotion classifier classifies the tweets into 11 emotions: joy, love, optimism, pessimism, trust, surprise, anticipation, sadness, anger, disgust and fear.

Uses a transformer model ([cardiffnlp/twitter-roberta-base-sentiment-latest](https://huggingface.co/cardiffnlp/twitter-roberta-base-sentiment-latest)) to classify sentiment and goes a step deeper and classify emotions of the tweets using another transformer model ([cardiffnlp/twitter-roberta-base-emotion-multilabel-latest](https://huggingface.co/cardiffnlp/twitter-roberta-base-emotion-multilabel-latest)).  
