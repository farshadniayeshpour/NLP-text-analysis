# NLP text analysis on Harry Potter books and Twitter data
This repository is a PyTorch implementation of Stanford CS224n (Winter 2018) using Harry Potter texts + Twitter data. 

Note: This material is only for personal research/study.

All credits to the wonderful implementation on https://github.com/DSKSD/DeepNLP-models-Pytorch

## Developed models:
1. Skipgram (word2vec) implementation using only Naive Softmax (01, 02)
2. GloVe (03)
3. RNN Language Modeling with LSTM (06)
4. Named Entity Recognition with Window Classification (04)
5. Twitter Sentiment Analysis with Convolutional Neural Network Text Classification (08)
6. Twitter Sentiment Analysis with FastText and pretrained twitter word embeddings

Note: I tried an advanced sentiment analysis with bidirectional 3 layer LSTM and the result was not impressive so I decided not to include the notebook in this series. 

The first four models are implemented on Harry Potter books (text available.) 

Due to the lack of sentiment annotation for Harry Potter books I decided to use Twitter data for sentiment analysis. 

## Future models include:
1. Recursive RNN (TreeLSTM) for sentiment classification (09)
2. Neural machine translation (possibly replaced by Sentiment Analysis) with Attention/Transformer (07)
3. Transformer implementation
4. Dynamic memory network for QA (10)
5. Advanced character-level CNN text classification for sentiment analysis
6. Pointer Sentinel Mixture Models

Feel free to pull requests!

Farshad Niayeshpour
farshadp.nia@gmail.com
