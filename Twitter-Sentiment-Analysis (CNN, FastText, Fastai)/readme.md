# Sentiment Analysis on Twitter data
In this project, we used a convolutional neural network for text classification. The end goal is to classify tweets by users into two categories: Positive and Negative

Twitter dataset is downloaded from: https://www.kaggle.com/kazanova/sentiment140

## CNN
Google pretrained word2vec word embeddings were downloaded from: https://github.com/mmihaltz/word2vec-GoogleNews-vectors

Pretrained word embeddings allow us to utilize transfer learning in our framework which improves our results. (0.68 MSE) 

In total, we optimized word embeddings of 672803 words with 300 embedding dimension. 3 convolutional kernels were used (bigram, trigram, and 4-gram.)

## FastText (by Facebook)
GloVe pretrained word embeddings (20, 50, 100, 200 dimensions) provided by Stanford NLP: https://nlp.stanford.edu/projects/glove/

We made use of pretrained Twitter word embeddings, appending bigrams to the end of sentences (as recommended by FAIR) and average pooling. 

## Fastai Language Model and Text Classifier

Next steps: 
- Character level CNN for text classification
- Advanced character-level CNN text classification for sentiment analysis


