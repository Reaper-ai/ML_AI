# Repo for my ML/AI models

## simple NN
simple nn traind on Fashion_MNIST dataset
Accuracy: 86.7%, Avg loss(Cross Entropy): 0.37927

 ## simple CNN
 two layer cnn on fashion mnist dataset
 Accuracy: 91.8%, Avg loss: 0.244397 

 ## Rnn
RNN from scratch made only using basic nn.module
terribly slow due to python loops, so dummy data is used

## Seq2Seq
Sequnce to Sequence encoder-decoder with LSTM, BLEU caps at 14, but loss rises.
using different data to fix, takes too long to train, sample data gives 6.8 BLEU

#3 Transformer 
Simple transformer implememnted from research paper, gets Bleu of 91 on test data
