# Handwritten Digits Classification

This project is an example of using machine learning to classify handwritten digits. It uses a Random Forest classifier to recognize and classify digits based on the pixel values of the images.

## Dataset

The dataset used for this project is the built-in "digits" dataset from scikit-learn. It contains images of handwritten digits from 0 to 9. Each image is represented as an 8x8 matrix of pixel values, and the goal is to predict the digit (label) based on these pixel values.

## Requirements

- Python 3.x
- numpy
- matplotlib
- scikit-learn (sklearn)

## Getting Started

1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the `handwritten_digits_classification.py` script to train the model and make predictions on the test set.

## Usage

Once you have set up the project and installed the required dependencies, you can run the `handwritten_digits_classification.py` script. It will load the dataset, split it into training and testing sets, create a Random Forest classifier, fit the classifier to the training data, and then make predictions on the test set.

The script will output the accuracy of the model on the test set and display a classification report and a confusion matrix.

## Customization

If you want to experiment with different models, hyperparameters, or even different datasets, you can modify the `handwritten_digits_classification.py` script accordingly. You might also explore different visualizations or additional analysis based on the data.

