In the Alphabet Soup Challenge workbook 3 different binary classification neural networds were applied to the data. 

For the three neural networks I started with a "shallow" deep neural network with 2 hidden layers with 24 neurons. The initial number of neurons and hidden layers is chosen arbitrarily. The model acheived an accuracy of 72.23%, and establishes the baseline accuracy to improve on.
The next two attempts to build a better model I increased the number of hidden layers and neurons per layer drastically. The second attempt has 3 hidden layers, with the layers having 50 or 100 neurons per layer. The second layer boasts an accuracy of 72.39%, and does not improve on the previous model. 
The third attempt I went with with 5 hidden layers with the same 50/100 neurons per layer. This model I thought would overfit the data and give an accuracy better than the second attempt, and it did. The third attempt achieved an accuracy of 72.43% and does not improve the previous models.

I was not able to achieve the target model performance of 75%. Through each attempt I attempted adding/removing hidden layers and neurons. I also changed the activation functions for many of the hidden layers, and settled on the sigmoind activation function for the outer layer gave the best performance. There are issues with using the rectified linear unit (reLU) and leaky reLU methods for this dataset.
If I were to implement a different model it would be worthwhile to explore ensemble trees/random forests with this dataset. There are a lot of categorical variables that a tree model may do well on. Perhaps the tree model can capture more of the "quirks" of the data versus the neural networks getting hung up on trying to find paths of relations in the dataset.









