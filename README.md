# 🌱 Plant Seedlings Image Classification using CNNs

A deep learning project to classify images of plant seedlings into one of 12 species using Convolutional Neural Networks (CNNs) in Keras. This work is inspired by a Kaggle challenge and built as part of a learning module provided by Great Learning.

---

## 📌 Problem Statement

The goal of this project is to create a CNN-based image classifier that can accurately determine the species of a plant seedling based on an image. This can aid in agricultural automation and environmental monitoring.

Dataset includes images of **12 plant species**, preprocessed and provided as `.npy` and `.csv` files.

---

## 🗃 Dataset

- **Source**: Adapted from the [Kaggle Plant Seedlings Classification](https://www.kaggle.com/c/plant-seedlings-classification)
- **Files used**:
  - `plantimages.npy`: Preprocessed images in NumPy array format.
  - `Labels.csv`: Labels associated with each image.

Due to dataset size constraints, original images have been resized to `128x128` and saved in `.npy` format for efficiency.

---

## 🧠 Techniques & Workflow

### 1. 📥 Data Loading & Visualization
- Loaded preprocessed data from `.npy` and `.csv`.
- Displayed sample images to understand variation in the dataset.

### 2. 🧼 Data Preprocessing
- **Normalization** of image pixel values.
- **Gaussian Blurring** to reduce image noise.
- Data split into training, validation, and testing sets.

### 3. 🔀 Label Encoding
- Converted class labels into one-hot encoded vectors for multi-class classification.

### 4. 🏗 CNN Model Building
- Built using **Keras Sequential API**.
- Layers used: `Conv2D`, `MaxPooling2D`, `Dropout`, `Flatten`, `Dense`.
- Loss function: `categorical_crossentropy`
- Optimizer: `Adam`

### 5. 📊 Evaluation
- Evaluated model on test data.
- Generated and analyzed a **confusion matrix**.
- Visualized predictions on selected test images.

---

## 🖼 Visual Results

Visualizations include:
- Raw and blurred images.
- Class-wise predictions.
- Sample image predictions like `x_test[2], x_test[3], x_test[33], x_test[36], x_test[59]`.

---

## 📁 Repository Structure

├── CNN_Project_Anyakwu_Chukwuemeka_Isaac2.ipynb # Main Jupyter notebook ├── CNN_Project_Anyakwu_Chukwuemeka_Isaac2.html # Rendered HTML version ├── Labels.csv # Image class labels ├── README.md # Project documentation

yaml
Copy
Edit

---

## 📚 Learning Outcomes

- Hands-on image classification using CNNs.
- Preprocessing and visualizing image data.
- Model tuning using Keras.
- Deployment-readiness for real-world image classification.

---

## ✅ Future Improvements

- Use **data augmentation** to boost performance.
- Try **transfer learning** with pretrained models like VGG16 or ResNet.
- Deploy the model via Flask API or Streamlit app.

---

## 📬 Contact

**Author**: Anyakwu Chukwuemeka Isaac  
Feel free to connect via [LinkedIn](#) or email.

---

## 📜 License

This project is for educational purposes only. All rights reserved © Great Learning.
