# Next-Word-Prediction-using-Bi-LSTM

Next word prediction is also called Language Modeling and it is the task of predicting what word comes next.It is one of the fundamental tasks of NLP.<br/>
<img src="https://user-images.githubusercontent.com/109072424/210736956-86b0f4e4-48c7-4546-9c2c-b380288e84f7.png" width="20%" height="20%">

## Bi-LSTM
Bidirectional recurrent neural networks(RNN) are really just putting two independent RNNs together. This structure allows the networks to have both backward and forward information about the sequence at every time step

Using bidirectional will run your inputs in two ways, one from past to future and one from future to past and what differs this approach from unidirectional is that in the LSTM that runs backward you preserve information from the future and using the two hidden states combined you are able in any point in time to preserve information from both past and future.

![image](https://user-images.githubusercontent.com/109072424/216575497-c5e99dbd-7bc0-42e8-9b78-b26409ed5e15.png)


The Bi-LSTM RNN model was trained on various articles collected from a site, which predicts the next word on the basis of input on which it has been trained upon.
