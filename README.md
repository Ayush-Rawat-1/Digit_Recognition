# Handwritten Digit Recognition Using CNN

## Overview

This project is a digit recognition application that leverages a Convolutional Neural Network (CNN) trained on the MNIST dataset. It uses Pygame to create an interactive window where users can write digits, and the model predicts the digit in real-time.

## Features

- *Handwritten Digit Recognition*: Write any digit (0-9) in the Pygame window, and the model will predict the digit.
- *Interactive Interface*: The Pygame window allows users to draw digits using their mouse.
- *Real-time Prediction*: The CNN model processes the handwritten input and provides predictions instantly.

## Requirements

- Python 3.x
- Pygame
- TensorFlow/Keras
- NumPy

You can install the required dependencies using:

bash
pip install pygame tensorflow numpy


## Dataset

The model is trained on the *MNIST dataset*, which consists of 60,000 training images and 10,000 test images of handwritten digits (0-9).

## Model Architecture

The CNN model used for digit recognition includes the following layers:

1. *Input Layer*: Accepts 28x28 grayscale images.
2. *Convolutional Layers*: Extracts features from the input images.
3. *Pooling Layers*: Reduces the spatial dimensions of the feature maps.
4. *Fully Connected Layers*: Classifies the extracted features into one of the 10 digit classes.
5. *Output Layer*: Produces probabilities for each digit (0-9).

## Usage

1. Clone the repository:

bash
git clone https://github.com/Ayush-Rawat-1/Digit_Recognition/
cd Digit_Recognition


2. Run the digit recognition script:

bash
python digit_recognition.py


3. A Pygame window will open where you can draw a digit using your mouse.

4. The predicted digit will be displayed on the screen.

## How It Works

- When you draw a digit in the Pygame window, the drawing is captured as a 28x28 image.
- The image is then fed into the CNN model, which processes it and predicts the digit.
- The prediction is displayed on the screen in real-time.

## Future Enhancements

- Improve the accuracy of the model by fine-tuning the architecture.
- Add more features to the Pygame interface, such as an eraser tool or undo functionality.
- Implement support for recognizing multiple digits in a single drawing.

## Contributing

Contributions are welcome! If you have ideas for improvements or have found a bug, please feel free to submit an issue or a pull request.

## License

This project is licensed under the MIT License.

---

This README provides a comprehensive overview of your project, guiding users on how to set up, run, and understand your digit recognition application.
