# CNN Classifier for Cats and Dogs

## Project Overview

This project implements a Convolutional Neural Network (CNN) for binary image classification of cats and dogs using TensorFlow and Keras. The model is trained on labeled image data and can predict whether a given image contains a cat or a dog.

The project demonstrates the complete deep learning workflow, including data preprocessing, image augmentation, CNN model development, training, evaluation, and prediction on unseen images.

---

## Features

* Image preprocessing and normalization
* Data augmentation using ImageDataGenerator
* Convolutional Neural Network (CNN) architecture
* Model training and validation
* Accuracy and loss visualization
* Prediction on new images

---

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Pillow
* Jupyter Notebook

---

## Repository Structure

```text
CNN_Classifier_Cats_and_Dogs/
│
├── CNN_Cat_Dog.ipynb
├── README.md
└── dog.webp
```

---

## Dataset

This project uses the Cats and Dogs image dataset.

Dataset Source:

https://www.kaggle.com/datasets/tongpython/cat-and-dog

After downloading and extracting the dataset, organize it as follows:

```text
dataset/
│
├── training_set/
│   ├── cats/
│   └── dogs/
│
└── test_set/
    ├── cats/
    └── dogs/
```

The dataset is not included in this repository due to its large size.

---

## CNN Architecture

The model consists of:

1. Input Layer
2. Convolution Layer (32 Filters)
3. Max Pooling Layer
4. Convolution Layer (64 Filters)
5. Max Pooling Layer
6. Flatten Layer
7. Dense Layer (128 Neurons)
8. Dropout Layer
9. Output Layer (Sigmoid Activation)

---

## Installation

Install the required libraries before running the notebook:

```bash
pip install tensorflow numpy matplotlib pillow scikit-learn
```

---

## How to Run

1. Download the dataset from the provided Kaggle link.
2. Place the dataset folder in the project directory.
3. Open Jupyter Notebook.
4. Open `CNN_Cat_Dog.ipynb`.
5. Run all cells sequentially.
6. Train the model and evaluate its performance.
7. Test predictions using new cat or dog images.

---

## Sample Prediction

Input Image:

```text
dog.webp
```

Predicted Output:

```text
Dog
```

---

## Learning Outcomes

This project helped in understanding:

* Deep Learning Fundamentals
* Convolutional Neural Networks (CNNs)
* Image Classification
* Feature Extraction
* Data Augmentation
* Model Evaluation and Prediction

---

## Future Enhancements

* Transfer Learning using VGG16, ResNet50, or EfficientNet
* Multi-class animal classification
* Real-time image prediction system
* Streamlit-based web application deployment
* Hyperparameter optimization

---

## Author

**Dikshitha Reddy Vanga**
