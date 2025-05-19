[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/r8OAyKH-)
# CNN Classification Task with Cat-vs-Dog dataset

## Task Description
In this task, you will build a Convolutional Neural Network (CNN) for image classification. The goal is to classify images into two categories: **dogs** and **cats**. You will:

1. Preprocess and explore the dataset.
2. Build and train a CNN classification model.
3. Evaluate the model's performance using appropriate metrics.
4. Record your findings and observations under the **Findings** section.


## Dataset
The dataset used for this task is **Dogs vs. Cats**:

[Kaggle Dataset - Dog vs. Cat](https://www.kaggle.com/datasets/anthonytherrien/dog-vs-cat)

### Dataset Details:
- **Content**: Images of dogs and cats.
- **Format**: JPEG images.
- **Labels**: 0 for cat, 1 for dog.


## Requirements

1. **Model Requirements**:
   - Build a CNN model.
   - Include at least:
     - Input layer for image data.
     - Multiple convolutional layers with appropriate activation functions.
     - Pooling layers (e.g., MaxPooling).
     - Fully connected layers leading to a softmax or sigmoid output.
   - Use **binary cross-entropy** as the loss function for binary classification.

2. **Evaluation**:
   - Use metrics such as **accuracy**, **precision**, **recall**, and **F1-score**.
   - Create visualizations for:
     - Model training and validation loss.
     - Model training and validation accuracy.
     - Confusion matrix.

3. **Documentation**:
   - Clearly document:
     - The architecture of the CNN model.
     - Evaluation results.

## Findings
Document your results and observations here:
1. For the first hyperparameter model:
   - **Accuracy**: 88%
   - **Loss**: 0.4693
   - **Observations**:
      - The CNN model seems to overfitts 
      - The loss seems to be a little bit acceptable
      - It may needs some techinique on improving & early stopping to solve the overfitts problem
2. For the second hyperparameter model:
   - **Accuracy**: ~94%
   - **Loss**: 0.12
   - **Observations**:
      - As we can see thats increasing the `stride` & `MaxPooling` helps to overcome the overfitting.
      - The `EarlyStopping` really efficient when it comes to trying to absolutly avoid the overfitting as we can see in the above figures.

Add more details as needed to describe your experiments and outcomes.


## References
- [TensorFlow Documentation](https://www.tensorflow.org/)
- [Keras Examples](https://keras.io/examples/)
- [Dataset on Kaggle](https://www.kaggle.com/datasets/anthonytherrien/dog-vs-cat)
