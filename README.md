Project Title: Cat-Dog Image Classifier using Support Vector Machine (SVM) and Histogram of Oriented Gradients (HOG)

Description:
This project focuses on building an image classifier capable of distinguishing between images of cats and dogs using Support Vector Machine (SVM) algorithm with Histogram of Oriented Gradients (HOG) features. The classifier is trained on a dataset of grayscale images resized to 64x64 pixels. The trained model is evaluated using metrics such as accuracy, precision, recall, and F1-score.

Dependencies:

Python 3.x
NumPy
scikit-learn
OpenCV (opencv-python)
scikit-image
Files Description:

train.py: Python script for training the SVM classifier. It preprocesses the training images, extracts HOG features, trains the SVM model using grid search and cross-validation, and evaluates the model's performance.

test.py: Python script for testing the trained SVM model. It loads the trained model, preprocesses test images, extracts HOG features, and predicts the labels. It also calculates accuracy and prints a classification report.

preprocess.py: Python module containing functions for preprocessing images. It includes functions for converting images to grayscale, resizing, and extracting HOG features.

requirements.txt: Text file listing all dependencies required to run the project.
