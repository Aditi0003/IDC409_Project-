# IDC409_Project-

data link: https://drive.google.com/file/d/1Dhzs3oA4xn0Dpi2AZ5TVu0H1cuZGat2R/view?usp=sharing

Approach:

We attempt to use neural networks (Using tensorflow keras) to build a model and train it using the data provided. First we standardise the data. Then we built a simple Multi-Layered Perceptron architecture with layers 625, 512, 225, 20, and 5 with few drop out layers in between to prevent overfitting. We trained this model on a standardised version of the data provided and obtained a classification accuracy of ~75%. 

We also tried to reduce the dimensionality of the data by using PCA (Principal component analysis). Then we trained the same neural network on this data. We could obtain an accuracy of ~71% with dimensionality reduced to 20. In general, the accuracy decreased slowly as we reduced the number of components.
