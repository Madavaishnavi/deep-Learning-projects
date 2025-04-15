# Image Classification using CNN

This project implements a Convolutional Neural Network (CNN) to classify images into different categories. It involves image preprocessing, data augmentation, model training, and performance evaluation using visual metrics.

##  Project Description

- **Objective:** Train a CNN model on a labeled image dataset to classify objects/images.
- **Architecture:** The CNN consists of multiple convolutional and pooling layers followed by dense layers.
- **Evaluation:** Accuracy, loss, and confusion matrix are visualized.

##  Features

- Image preprocessing and normalization
- Data augmentation using Keras `ImageDataGenerator`
- Model architecture with dropout and batch normalization
- Accuracy: ~94% on test set
- Confusion matrix and class-wise performance

## Results

- Training Accuracy: ~98%
- Validation Accuracy: ~94%
- Loss curves show convergence after ~10 epochs

### Confusion Matrix (Excerpt)

| Actual | Predicted | Count |
|--------|-----------|-------|
| Class A | Class A | 95 |
| Class B | Class B | 90 |
| Class C | Class B | 3 |

##  Libraries

- TensorFlow / Keras
- NumPy, Matplotlib, Seaborn
- scikit-learn

---

##  How to Run

1. Clone the repository
2. Navigate to `Image-Classification-CNN/`
3. Open and run the `Image_Classification_CNN.ipynb` notebook in Jupyter
