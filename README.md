# NeuralNetworkFromScratch

### Problem Statement:
In this project we are trying to tackle digit classification by using the MNIST dataset(https://www.wikiwand.com/en/MNIST_database).

What is the MNIST dataset? Large database of 28 by 28 low res grayscale images of handwritten digits.

GOAL: Building a neural network that classifies images of handwritten digits and tells you what digit is written in that image. We will have a simple NN with 2 layers. The first input layer will have 784 nodes. Each 784 picle maps to a node. The second layer or hidden layer will have 10 units and our output layer will have 10 units each corresponsing to one digit that can be predicted. 

### PLAN: 
1. Start with 28 * 28 pixel training images. 784 pixels overall. Each value is between 0(black) and 255(white) and we have m of these training images which can be represented as below: 
```

    ┌ -- x(1) -- ┐ T
    
    | -- x(2) -- |
    
X = | -- x(3) -- |     each row is 784 columns long corresponding to each pixel in the image

    | --  ..  -- |
    
    | --  ..  -- |
    
    └ -- x(m) -- ┘
    
 ```
    
 what are we going to work with is the transpose where each column will be one example which means we will have m columns.
 
 ### Training:
 Traning this involved 3 parts:
 
 1. Forward propogation

![IMG_6215](https://github.com/AarohiChopra/NeuralNetworkFromScratch/assets/51353233/e5c6dfd9-f023-4fd5-8187-e605711e9ea5)

 2. Backward propogation

![IMG_6216](https://github.com/AarohiChopra/NeuralNetworkFromScratch/assets/51353233/52e930d6-251d-49fc-9ca4-74a503ff9a43)

 3. Update Parameters
 
 
 
 
