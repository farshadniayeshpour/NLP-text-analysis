# NLP text analysis on Harry Potter books and Twitter data
This repository is a PyTorch implementation of Stanford CS224n (Winter 2018) using Harry Potter texts + Twitter data. 

Note: This material is only for personal research/study.

All credits to the wonderful implementation on https://github.com/DSKSD/DeepNLP-models-Pytorch

Developed models are as follows:
1. Skipgram (word2vec) implementation using only Naive Softmax (01, 02)
2. GloVe (03)
3. RNN Language Modeling with LSTM (06)
4. Named Entity Recognition with Window Classification (04)
5. Twitter Sentiment Analysis with Convolutional Neural Network Text Classification (08)

The first four models are implemented on Harry Potter books (text available.) 
Due to the lack of sentiment annotation for Harry Potter books I decided to use Twitter data for sentiment analysis. 

Future models include:
1. Recursive RNN for sentiment classification (09)
2. Neural machine translation (or any other applicable topics) with Attention/Transformer (07)
3. Transformer implementation
4. Dynamic memory network for QA (10)
5. More sentiment analysis with these modifications
  - pre-trained word embeddings
  - different RNN architecture
  - bidirectional RNN
  - multi-layer RNN
  - regularization
  - a different optimizer
 6. Advanced character-level CNN text classification for sentiment analysis
 7. Pointer Sentinel Mixture Models

Feel free to pull requests!

Farshad Niayeshpour
farshadp.nia@gmail.com
