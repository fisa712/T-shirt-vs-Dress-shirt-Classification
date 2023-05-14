<!-- # T-shirt-vs-Dress-shirt-Classification -->
<!-- An implementation of a machine learning algorithm to classify T-shirt and Dress shirt. -->

# T-shirt vs Dress-shirt Classification

This repository contains the code for a machine learning model that classifies images of T-shirts and dress-shirts. The model uses the Histogram of Oriented Gradients (HOG) feature descriptor to extract features from the images and then applies two classification techniques: Decision Trees and Support Vector Machines (SVM).

## Dataset

The dataset used for training and testing consists of the following files:

- `TrainData.csv`: Contains 12,000 training examples. Each row represents a flattened 28x28 pixel gray-scale image.
- `TrainLabels.csv`: Provides true labels for the training examples. T-shirts are labeled as 1, and dress-shirts are labeled as -1.
- `TestData.csv`: Contains test examples for evaluating the model.

## Code Structure

- `extract_features.py`: This script extracts HOG features from the images in the dataset.
- `train_model.py`: Trains the machine learning model using the extracted features and evaluates its performance.
- `utils.py`: Contains utility functions used in the project.

## Usage

1. Ensure that you have the required dependencies installed (scikit-learn, numpy, matplotlib).
2. Run `extract_features.py` to extract HOG features from the images. The features will be saved as `features.npy`.
3. Run `train_model.py` to train the model using the extracted features and evaluate its accuracy on the test set.

## Results

The accuracy of the trained models on the test set is as follows:
- Decision Trees: 71.75%
- Support Vector Machines: 77.5 %

Note: The accuracy score may vary depending on the specific execution.

Feel free to modify and experiment with the code to further improve the classification performance or explore other machine learning techniques.

## Credits

This assignment is part of Course Programming For AI. The dataset used in this project is derived from the Fashion-MNIST dataset.

If you have any questions or suggestions, please feel free to contact me.

Happy coding!
