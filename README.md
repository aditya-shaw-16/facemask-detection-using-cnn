# Face Mask Detection using AI

This project implements a face mask detection system using deep learning techniques. It employs TensorFlow and Keras for model training and evaluation. The model is trained to classify images of individuals with and without face masks.

## Features

- Dataset preprocessing using image augmentation.
- Training a convolutional neural network (CNN) for classification.
- Model evaluation with confusion matrix and classification report.
- Achieved high accuracy of **98%**.
- Integration with Google Colab for cloud-based execution.

## Libraries Used

The following libraries are used in the project:

- **TensorFlow and Keras**: For building and training the neural network.
- **OpenCV**: For image processing.
- **NumPy**: For numerical computations.
- **Scikit-learn**: For evaluation metrics.
- **Google Colab Utilities**: For mounting and accessing Google Drive.

## Dataset

The dataset used in this project contains images of individuals with and without face masks. The dataset is structured into two main categories:

- **With Mask**: Images of people wearing face masks.
- **Without Mask**: Images of people without face masks.

Ensure the dataset is organized into separate folders for each class:


###If you are using a custom dataset, ensure it follows the same structure.

## How to Use

1. Clone this repository or upload the notebook to your environment.
2. Install the required dependencies:
   ```bash
   pip install tensorflow opencv-python numpy scikit-learn

