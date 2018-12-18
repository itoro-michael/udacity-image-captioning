# Computer Vision Nanodegree

The Image Captioning project, is the second project in the Computer Vision Nanodegree from Udacity.

## Image Captioning
>[CVND---Image-Captioning-Project-master](https://github.com/itoro-michael/udacity-image-captioning/tree/master/CVND---Image-Captioning-Project-master)

The CNN-RNN architecture consists of a convolutional neural network (CNN) with 50 layer deep residual network obtained from TorchVision and a recurrent neural network (RNN) built with the long short-term memory (LSTM) cell. There is an embbeding layer that transforms the input caption tokens to the embedding dimension required by the RNN. The embedding feature size is 512. The LSTM cell has a hidden output size of 512. The output of the LSTM network goes through a dropout layer before being applied to a fully connected layer that yields the final prediction of the RNN. The choice of the hyperparameters was mainly influenced by the Show and tell paper (Vinyals, O. et.al., 2015), however the batch size chosen was based on the Show, attend and tell paper (Xu, K. et.al., 2015).
