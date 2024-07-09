# Dog-Vision (🐶👁)

Welcome to Dog-Vision, a project that harnesses the power of Computer Vision to classify photos of dogs into different breeds using TensorFlow. Whether you're a dog lover or a machine learning enthusiast, this project provides a hands-on exploration of deep learning and transfer learning in the realm of computer vision.

## Project Overview

### Problem Statement

The objective of this project is to develop a multi-class classification model capable of identifying the breed of a dog from an input image. The model is trained on a diverse dataset consisting of over 20,000 images spanning 120 different dog breeds from the Stanford Dogs Dataset.

### Technology Stack

- **TensorFlow**: Leveraging the TensorFlow framework to build and train our deep learning model.
- **Deep Learning**: Exploring deep neural networks for feature extraction and classification.
- **Transfer Learning**: Harnessing pre-trained models to boost the performance of our custom dog breed classifier.

## Workflow

### 1. Data Collection

The dataset used for training and testing our model is sourced from the Stanford Dogs Dataset. It includes a vast array of dog images, each labeled with its respective breed.

### 2. Data Preprocessing

Prior to feeding the data into our model, we preprocess the images, ensuring they are appropriately sized, normalized, and ready for training.

### 3. Model Architecture

Our deep learning model is designed for multi-class classification, with layers configured for feature extraction and breed prediction.

### 4. Training

The model is trained on the preprocessed dataset using transfer learning. This step allows us to leverage the knowledge gained by pre-trained models like MobileNetV2, enhancing our model's ability to recognize intricate features in dog images.

### 5. Evaluation

The model's performance is evaluated on a separate test dataset to ensure its effectiveness in classifying unseen images.

### 6. Prediction

Finally, the trained model can be used to predict the breed of a dog in any given image.

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/rujuldwivedi/Dog-Vision.git`
2. Run the Jupyter notebook: `jupyter notebook Dog-Vision.ipynb`

## Contributing

Contributions are welcome! Feel free to open issues, submit pull requests, or suggest improvements. Let's work together to make Dog-Vision even better.

## Acknowledgments

Special thanks to the creators of the Stanford Dogs Dataset for providing a comprehensive and diverse collection of dog images for research and development.
