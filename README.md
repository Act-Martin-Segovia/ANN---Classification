# ANN---Classification

Three Artificial Neural Networks (ANNs) with different architectures were trained to perform image classification with the Fashion-MNIST dataset, and their performance was evaluated based on accuracy and loss.

**ANN 1**: The simplest architecture with two hidden layers showed early signs of overfitting, with validation accuracy stagnating and loss increasing after epoch 10. Despite this, it achieved a reasonable accuracy of 88.87%.

**ANN 2**: Adding a third hidden layer reduced the validation loss but still exhibited overfitting after epoch 10, achieving an accuracy of 88.52%. The additional complexity did not significantly improve performance compared to ANN 1.

**ANN 3**: By introducing batch normalization and dropout layers, the third model mitigated overfitting and continued to improve both validation accuracy and loss throughout the training process. This model achieved the highest accuracy of 89.27% and the lowest loss (0.2943), demonstrating that these regularization techniques can significantly enhance model generalization.

Overall, the results show that more complex architectures, combined with regularization techniques like batch normalization and dropout, can improve performance in image classification tasks by reducing overfitting and improving generalization to unseen data.
