# CIFAR-10 Multi-Model Image Classification

## Project Overview

This project is a deep learning image classification system using the **CIFAR-10 dataset**.

The main goal of the project is to train and compare different Artificial Intelligence models and determine which model gives the best performance for image classification.

The project was implemented using **Python, TensorFlow, and Keras**.

---

## Dataset

The project uses the **CIFAR-10 dataset**, which contains 60,000 color images divided into 10 classes.

Each image has a size of **32x32 pixels**.

### CIFAR-10 Classes

1. Airplane
2. Automobile
3. Bird
4. Cat
5. Deer
6. Dog
7. Frog
8. Horse
9. Ship
10. Truck

The dataset is divided into:

- 50,000 training images
- 10,000 testing images

---

## Models Used

This project compares six different deep learning models:

1. ANN Artificial Neural Network
2. Simple CNN
3. Improved CNN
4. Deep CNN
5. CNN with Data Augmentation
6. Transfer Learning using MobileNetV2

---

## Project Workflow

The project follows these steps:

1. Download CIFAR-10 dataset
2. Extract and load the dataset
3. Display sample images
4. Build multiple deep learning models
5. Train each model
6. Evaluate model performance
7. Compare all models
8. Display accuracy and loss graphs
9. Generate confusion matrix
10. Generate classification report
11. Save trained models

---

## Deep Learning Concepts Used

### Artificial Neural Network ANN

ANN is a basic neural network model. It flattens the image into one vector before classification.

ANN is not very strong for image classification because it loses spatial image information.

### Convolutional Neural Network CNN

CNN is better for image processing because it keeps the spatial structure of the image and learns important visual features such as edges, shapes, and textures.

### Batch Normalization

Batch Normalization improves training stability and helps the model learn faster.

### Dropout

Dropout is used to reduce overfitting by randomly disabling some neurons during training.

### Data Augmentation

Data Augmentation creates random variations of training images, such as flipping, rotating, zooming, and shifting.

This helps the model generalize better to new images.

### Transfer Learning

Transfer Learning uses a model that was already trained on a large dataset.

In this project, MobileNetV2 was used with pretrained ImageNet weights.

---

## Model Results

| Model | Test Accuracy |
|---|---:|
| ANN | 41.38% |
| Simple CNN | 69.82% |
| Improved CNN | 81.46% |
| Deep CNN | 84.03% |
| CNN with Data Augmentation | 77.61% |
| Transfer Learning MobileNetV2 | 86.68% |

---

## Best Model

The best model was:

**Transfer Learning using MobileNetV2**

It achieved the highest test accuracy:

**86.68%**

This model performed better because it used pretrained ImageNet features, which helped it recognize image patterns more effectively.

---

## Final Conclusion

In this project, six deep learning models were trained and tested on the CIFAR-10 image classification dataset.

The results showed that CNN-based models performed much better than the ANN model because CNNs are designed to understand image structure and extract visual features.

The ANN model achieved the lowest accuracy because it flattened the images and lost important spatial information.

The Deep CNN model achieved strong performance with an accuracy of 84.03%, showing that deeper convolutional networks can learn better image features.

The best model was Transfer Learning using MobileNetV2, which achieved an accuracy of 86.68%. This model performed the best because it used pretrained knowledge from ImageNet.

Overall, the project proves that CNN architectures and transfer learning are powerful techniques for image classification tasks.

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab
- GitHub

---

## How to Run the Project

1. Open the notebook in Google Colab.
2. Change runtime type to GPU.
3. Run all cells from top to bottom.
4. Wait until all models finish training.
5. Check the final model comparison table and graphs.

---

## Output Files

The project saves the trained models:

- ann_cifar10_model.keras
- simple_cnn_cifar10_model.keras
- improved_cnn_cifar10_model.keras
- deep_cnn_cifar10_model.keras
- augmented_cnn_cifar10_model.keras
- mobilenetv2_transfer_cifar10_model.keras

It also saves the model comparison results:

- cifar10_model_comparison_results.csv

---

## Project Status

Project completed successfully.
