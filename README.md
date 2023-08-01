# Digit Recognition with Neural Network v1.0.0

  This is a program, made in C++ with SDL2, to present a fun way to see a neural network working on prediction of digits from 0 a 9, from an image of 28x28 pixels.

  It works by reading weights and bias from a neural network, trained in python with TensorFlow. The used database is from Digit Recognition from Kaggle website and was trained with data augmentation.

  The neural network was constructed with 784 neurons at the input layer, 64 neurons at the hidden layer and 10 neurons at the output layer.

## Requirements

  For this program to work, we need 4 files:
  - The first file is located at `data/HiddenBias.txt`. It's the values of the neurons bias at the hidden layer.
  - The second file is located at `data/HiddenWeights.txt`. It's the values of the neurons weights at the hidden layer, connected with the input layer.
  - The third file is located at `data/OutputBias.txt`. It's the values of the neurons bias at the output layer.
  - The fourth file is located at `data/OutputWeights.txt`. It's the values of the neurons weights at the hidden layer, connected with the output layer.

## Working

  At the left of the window, we have a board, representing the image to be the input of the neural network. You can draw at this board using the mouse left click, erased with the mouse right click and to clear the board 'E' at the keyboard. 

<p align="left">
  <img src="https://github.com/DanB2S/DigitRecognition/assets/77987747/8969053a-8bd6-4948-8f67-aa21de8e5ee1" width="560" title="Board">
</p>

  At the right, we have a representation of the neural network of the board image.

<p align="left">
  <img src="https://github.com/DanB2S/DigitRecognition/assets/77987747/528bff3c-d790-42f7-a791-28543a764e39" width="560" title="Board">
</p>

## Future Update

  - I'm planning to update the neural network frontend, to be more clean and with more information.
  - Create a form of training the neural network.
  - Better accuracy.

## Creator

  - Daniel (@DanB2S)
