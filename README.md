# LSTM Network

LSTM stands for Long Short-Term Memory. It is a special type of Recurrent Neural Network (RNN) designed to process sequential data. 
Traditional RNNs can suffer from the vanishing gradient problem, which makes it difficult to remember information from earlier parts of a long sequence.
LSTM solves this problem using a memory mechanism and special gates.
An LSTM contains three major gates:
  1. Forget Gate - Determines which information from the previous cell state should be discarded.
  2. Input Gate - Determines which new information should be stored in the cell state.
  3. Output Gate - Determines which information should be passed to the next layer/output.
