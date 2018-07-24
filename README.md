# MNIST
- 28x28 images of handwritten numbers
- output is value between 0-9 

#### MultiLayer Perceptron and CNN implementation using Tensoflow and Keras

 
## Tensorflow
1. Model 1: input (784) - sigmoid(512) - sigmoid(128) - softmax(output 10)
  - Model 1 + AdamOptimizer
  - model 1 + gradient descent optimizer
2. Model 2 : input 784 - relu 512 - relu 128 - sigmoid 10
3. Model 3 : input - sigmoid ( Batch normalization 512) - sigmoid(Batch-normalization 128 ) - sigmoid output
4. Input : relu512 - dropout-relu128 - dropout-sigmoid


## Keras - MLP

1. MLP + sigmoid activation + SGD optimizer 
2. MLP + Sigmoid activation + ADAM
3. MLP + ReLu + SGD
4. MLP + Relu + Adam
5. MLP + Batch - Norm on hidden layers + Adam optimizer
6. MLP + dropout + Adam
7. Hyper-parameter tuning of Keras models using Sklearn

## Keras - Basic CNN
1. model with filter size 3x3

## Keras - CNN Variations
1. filter size 3x3
2. filter size 2x2
3. filter size 5x5 
- all the loss plots for basic and complex networks.
