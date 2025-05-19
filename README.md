# 🐶🐱 Cats vs Dogs - CNN Image Classification

## 📌 Overview
This project is part of my AI Bootcamp journey, where I implemented a **Convolutional Neural Network (CNN)** to classify images of cats and dogs. The goal is to explore deep learning techniques for image classification, improve performance through experimentation, and reflect on the training process.

## 🧠 What I Did
- Preprocessed and explored the dataset.
- Built and trained multiple CNN models using TensorFlow & Keras.
- Tuned hyperparameters to overcome overfitting and boost accuracy.
- Evaluated the model using standard classification metrics.
- Visualized training performance and results.
- Documented my findings and lessons learned.

---

## 📂 Dataset
The dataset used is the well-known **Dogs vs. Cats** dataset:

🔗 [Kaggle: Dog vs. Cat](https://www.kaggle.com/datasets/anthonytherrien/dog-vs-cat)

**Dataset Details:**
- Format: JPEG images
- Categories: 0 = Cat, 1 = Dog

---

## 🧪 Model Architecture & Requirements

### 🧱 CNN Architecture Includes:
- Input layer for 224x224 resized images
- Multiple convolutional layers with ReLU activations
- MaxPooling layers to reduce spatial dimensions
- Fully connected (dense) layers
- Sigmoid output layer for binary classification

### ⚙️ Loss & Metrics
- **Loss Function**: Binary Cross-Entropy
- **Evaluation Metrics**:
  - Accuracy
  - Precision
  - Recall
  - F1-Score

### 📊 Visualizations
- Training/validation accuracy & loss plots
- Confusion matrix for model evaluation

---

## 📈 Results & Observations

### 🔁 Model 1 (Baseline Hyperparameters)
- **Accuracy**: ~88%
- **Loss**: 0.4693
- **Observations**:
  - Signs of overfitting noticed after a few epochs
  - Acceptable loss but model could be more robust
  - No use of regularization or early stopping

### 🧪 Model 2 (Tuned Hyperparameters)
- **Accuracy**: ~94%
- **Loss**: 0.12
- **Observations**:
  - Using `stride` adjustments and `MaxPooling` improved generalization
  - Adding `EarlyStopping` helped reduce overfitting significantly
  - More stable training and better validation performance

> I might explore adding dropout or batch normalization in future versions.

---

## 📚 References
- [TensorFlow Documentation](https://www.tensorflow.org/)
- [Keras Examples](https://keras.io/examples/)
- [Dogs vs. Cats Dataset](https://www.kaggle.com/datasets/anthonytherrien/dog-vs-cat)

---

## 🙌 Credits
This project was developed as part of the **AI Model Building & Development Bootcamp** at Tuwaiq Academy. Special thanks to our instructors for their guidance throughout the course.
