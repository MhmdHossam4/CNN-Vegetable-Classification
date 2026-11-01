# 🥦 Vegetable Image Classification Using CNN

## 📌 Project Overview

This project focuses on classifying vegetable images using a Convolutional Neural Network (CNN) built from scratch with TensorFlow and Keras.

The model can classify images into 15 different vegetable categories. The main goal is to understand how CNNs work and apply deep learning techniques to an image classification task.

## 📂 Dataset

The project uses the **Vegetable Image Dataset** from Kaggle.

The dataset contains 15 vegetable classes:

- Bean
- Bitter Gourd
- Bottle Gourd
- Brinjal
- Broccoli
- Cabbage
- Capsicum
- Carrot
- Cauliflower
- Cucumber
- Papaya
- Potato
- Pumpkin
- Radish
- Tomato

The original dataset is divided into three folders:

- Training
- Validation
- Testing

**Dataset Link:** [Vegetable Image Dataset - Kaggle](https://www.kaggle.com/datasets/misrakahmed/vegetable-image-dataset)

## 🛠️ Technologies & Libraries

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn

## ⚙️ Project Workflow

1. **Data Exploration:** Count images in each vegetable class and analyze the dataset distribution.
2. **Data Preprocessing:** Resize images to 224 × 224 pixels and normalize pixel values.
3. **Data Augmentation:** Apply rotation, shifting, shearing, zooming, and horizontal flipping to training images.
4. **Data Loading:** Load images in batches using `ImageDataGenerator` and `flow_from_directory()`.
5. **Model Building:** Build a CNN model from scratch using convolutional and pooling layers.
6. **Model Training:** Train the model using Adam optimizer and categorical cross-entropy loss.
7. **Early Stopping:** Use EarlyStopping to monitor validation loss and restore the best model weights.
8. **Model Evaluation:** Evaluate training and validation performance and visualize accuracy and loss curves.

## 🧠 CNN Architecture

The CNN model consists of:

- Conv2D layer with 32 filters + MaxPooling2D
- Conv2D layer with 64 filters + MaxPooling2D
- Conv2D layer with 128 filters + MaxPooling2D
- Flatten layer
- Dense layer with 512 neurons and ReLU activation
- Dropout layer (0.5)
- Output layer with 15 neurons and Softmax activation

## 📊 Model Results

The model achieved the following results:

| Metric | Result |
|---|---:|
| Training Accuracy | 96.84% |
| Validation Accuracy | 97.83% |
| Training Loss | 0.1059 |
| Validation Loss | 0.0646 |

The results show good performance on both training and validation data, with no clear sign of overfitting.

## 📈 Evaluation

Training and validation accuracy and loss curves were used to monitor the model's learning process and performance.

## 🎯 What I Learned

Through this project, I practiced:

- Understanding CNN architecture.
- Image preprocessing and data augmentation.
- Building and training a deep learning model.
- Using TensorFlow and Keras.
- Evaluating classification models.

---

**Note:** This project was developed as part of a Deep Learning assignment and for practical learning.
