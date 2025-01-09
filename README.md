## Human Action Recognition on Videos

In this project I use [Convolutional Lstm neural network](https://arxiv.org/abs/1506.04214) which is a combination of Convolutional and Long Short-Term memory allowing for 
spatial dependencies in data sequences like videos to be captured efficiently over time.

The dataset is [here](https://www.kaggle.com/datasets/pypiahmad/realistic-action-recognition-ucf50-dataset).\
I implemented this neural network in both Pytorch and Keras.\
I optimized the hyperparameters by training and testing the model over and over again, each time with different settings.\
Due to GPU limitaions I restricted 11 classes of original dataset to only 'Biking' and 'Horse Riding' and our model achieved an accuracy of over 80.
