# Face-Recognition-Model
# Face Recognition Model Using TensorFlow

This project demonstrates the development of a face recognition model using TensorFlow and transfer learning with MobileNetV2. The model predicts the identity of a person based on an input image.

## Dataset

The dataset should be organized into subdirectories for each person's images, ensuring that images of the same person are stored in the same folder.

## Installation

Install the required packages using:


pip install tensorflow numpy matplotlib

#Usage

Ensure your dataset is properly organized.
Run the provided training script to train the model.
Model Training
The model uses MobileNetV2 as the base model, with additional custom layers and dropout regularization to prevent overfitting. The training process includes data augmentation to enhance the model's robustness. Early stopping is used to prevent overfitting by monitoring the validation loss.

#Evaluation

Evaluate the trained model using the validation set and visualize the training process with accuracy and loss plots.

#Overfitting Strategies

To mitigate overfitting, the following strategies have been employed:

Dropout regularization
Data augmentation
Early stopping

#Results

The model outputs validation loss and accuracy after training. Use the plotted graphs to observe the model's performance and check for overfitting.
