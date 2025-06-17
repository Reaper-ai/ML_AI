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

# Seq2Seq
Sequnce to Sequence encoder-decoder with LSTM, BLEU caps at 14, but loss rises ? 

# TRansformer 
Data is simple so the transformer overfits. adding even a signle dropout causes Bleu to fall to 0 aand loss to spike
