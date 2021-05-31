# Handwritten Digit Recognition

![hqdefault](https://user-images.githubusercontent.com/52822987/120145595-675f8080-c201-11eb-8a1a-c0629f776ff1.jpg)

# About
Handwriting recognition (HWR), also known as Handwritten Text Recognition (HTR), is the ability of a computer to receive and interpret intelligible handwritten input from sources such as paper documents, photographs, touch-screens and other devices. 

# Technique

# Step 1:

1. For this task we build a convolution neural network (CNN) in Keras using Tensorflow backend. 

![1](https://user-images.githubusercontent.com/52822987/120145875-d8069d00-c201-11eb-9da7-4c147b2554f1.jpeg)

2. We will use a standard CNN with multiple convolution and maxpool layers, a few dense layers and a final output layer with softmax activation.

# Maxpooling

![max](https://user-images.githubusercontent.com/52822987/120146068-2320b000-c202-11eb-8300-8733b46fb190.png)

# Softmax

![softmax](https://user-images.githubusercontent.com/52822987/120146102-329ff900-c202-11eb-96a0-0da23bcd33ad.png)



3. RELU activation was used between the convolution and dense layers and model was optimized using Adam optimizer. 

# ReLU
![relu](https://user-images.githubusercontent.com/52822987/120146188-55321200-c202-11eb-85bf-bfcb4fa44ee6.png)

# Adam
![adam](https://user-images.githubusercontent.com/52822987/120146212-5c592000-c202-11eb-989e-4c3ebdd11494.jpg)

4. The size of the model needs to be proportional to the size of the data. 


5. Three blocks of convolution -maxpool layers and couple of dense layers was sufficient for this problem.


