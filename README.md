# 🧠 CNN-based Image Classification on CIFAR-10

<p align="center">
Deep Learning project that classifies images into 10 categories using a Convolutional Neural Network (CNN).
</p>

---

## 📌 Project Overview

```text
This project implements an Image Classification model using a
Convolutional Neural Network (CNN) trained on the CIFAR-10 dataset.

The model learns visual patterns such as edges, shapes, and textures
to correctly classify images into one of ten object categories.
```

CNNs are widely used in **Computer Vision tasks** because they can automatically extract important features from images.

---

## 📂 Dataset Information

```text
Dataset Name : CIFAR-10
Total Images : 60,000
Training Images : 50,000
Testing Images : 10,000
Image Size : 32 × 32 pixels
Color Channels : RGB (3 channels)
Number of Classes : 10
```

### Classes in CIFAR-10

```text
Airplane
Automobile
Bird
Cat
Deer
Dog
Frog
Horse
Ship
Truck
```

Each image belongs to **one of these 10 categories**.

---

## ⚙️ Technologies Used

```text
✔ Python
✔ TensorFlow / Keras
✔ NumPy
✔ Matplotlib
✔ Scikit-Learn
```

---

## 🧠 CNN Model Architecture

```text
Input Layer
32 × 32 × 3 RGB Image
        ↓

Convolution Layer
Extracts image features (edges, shapes)
        ↓

ReLU Activation
Introduces non-linearity
        ↓

Max Pooling Layer
Reduces spatial dimensions
        ↓

Convolution + Pooling Layers
Extract deeper visual patterns
        ↓

Flatten Layer
Convert feature maps into 1D vector
        ↓

Dense Layer
Fully connected neural network
        ↓

Output Layer
10 neurons (10 classes)
Activation : Softmax
```

---

## 🔄 Project Workflow

```text
1️⃣ Load CIFAR-10 dataset
2️⃣ Normalize pixel values (0–255 → 0–1)
3️⃣ Split into training and testing datasets
4️⃣ Build CNN model architecture
5️⃣ Train model using epochs
6️⃣ Evaluate model performance
7️⃣ Predict image classes
```

---

## 🧪 Model Training Example

```python
model.fit(
    X_train,
    y_train,
    epochs=20,
    batch_size=64,
    validation_data=(X_test, y_test)
)
```

### What is an Epoch?

```text
Epoch = One complete pass of the entire training dataset
through the neural network.
```

Example:

```text
Epoch 1 → Model sees all training images once
Epoch 10 → Model improves its understanding
Epoch 20 → Model becomes more accurate
```

---

## 📊 Model Performance

```text
Training Accuracy : ~85–90%
Testing Accuracy  : ~80–85%
Loss Function     : Categorical Crossentropy
Optimizer         : Adam
```

CNN performs well because it **captures spatial features and patterns in images**.

---

## 📁 Project Structure

```text
CIFAR10-CNN-Image-Classifier
│
├── train_model.py
├── cnn_model.py
├── dataset_loader.py
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/cifar10-cnn-classifier.git
```

### 2️⃣ Install Dependencies

```bash
pip install tensorflow numpy matplotlib scikit-learn
```

### 3️⃣ Run the Training Script

```bash
python train_model.py
```

---

## 🎯 Applications

```text
✔ Image recognition systems
✔ Self-driving car vision systems
✔ Security surveillance systems
✔ Object detection
✔ Smart photo organization
```

---

## 👨‍💻 Author

```text
Name : Om Prakash Kannaujiya
GitHub : https://github.com/yourusername
```

---

⭐ If you like this project, consider giving it a **Star ⭐ on GitHub**.
