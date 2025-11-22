# Dog vs Cat Image Classifier Using SVM

This project demonstrates a simple image classification pipeline to distinguish between dogs and cats using a Support Vector Machine (SVM). It loads grayscale images, preprocesses them, trains a linear SVM model, evaluates performance, and visualizes predictions.


## Features

- Loads images from directories (`dog` and `cat` folders)
- Converts images to grayscale and resizes to 100x100 pixels
- Flattens and normalizes image data for SVM input
- Trains a linear SVM classifier on the dataset
- Evaluates model with classification report and confusion matrix
- Visualizes sample predictions with actual vs predicted labels
- Saves the trained model to disk for future use

  
## Requirements

- Python 3.x
- OpenCV (`cv2`)
- NumPy
- tqdm
- matplotlib
- scikit-learn
- seaborn
- joblib
