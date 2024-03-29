# Hollywood Celebrity Classifier Project

## Overview

The Hollywood Celebrity Classifier is a machine learning project designed to identify celebrities from images. It takes an image as input and outputs the probabilities of the image being a particular actor. This project is an excellent example of a classification problem solved using advanced computer vision techniques and machine learning algorithms.

## Features

- **Celebrity Recognition**: Classify images to identify Hollywood celebrities with high accuracy.
- **Advanced Image Processing**: Utilizes wavelet transforms for feature extraction, enhancing the classifier's performance on varied image conditions.
- **Machine Learning at Core**: Employs Support Vector Machine (SVM) for efficient and robust classification.
- **OpenCV Integration**: Makes use of OpenCV Haarcascades for preliminary face detection, ensuring that the classifier focuses on the relevant parts of an image.

## How It Works

1. **Preprocessing**: Images are first processed using OpenCV Haarcascades to detect faces in the images.
2. **Feature Extraction**: Wavelet transforms are applied to the detected faces to extract meaningful features from the images.
3. **Classification**: The extracted features are then fed into a Support Vector Machine (SVM) classifier that has been trained to recognize various Hollywood celebrities.
4. **Output**: The classifier outputs the probabilities of the image being each actor, helping users identify the celebrity in the image.

## Installation

To set up the Hollywood Celebrity Classifier project on your local machine, follow these steps:

1. **Clone the Repository**
2. **Install Dependencies**
3. **Run the Application**
- Instructions on how to run the application, including any command-line arguments or scripts.

## Usage

- Detailed usage instructions, including example commands to classify an image.
- Any options or configurations that can be set.

## Dataset

- Information about the dataset used for training the classifier, including sources, number of images, and how the dataset can be accessed or generated.

## Technologies Used

- **Python**: Primary programming language.
- **OpenCV**: For image processing and face detection.
- **Wavelet Transform**: For feature extraction from images.
- **Support Vector Machine (SVM)**: For classifying the extracted features into different celebrities.

