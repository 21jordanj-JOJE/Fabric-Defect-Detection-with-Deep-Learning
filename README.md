# CNN-Based Surface Defect Classification Using Deep Learning

## Project Overview

This project focuses on the classification of fabric surface defects using **Convolutional Neural Networks (CNN)** and **Transfer Learning (MobileNetV2)**. The model is trained to identify and classify surface defects from images into different categories such as **Hole** and **Lines**.

The aim of this project is to automate industrial defect inspection and improve quality control using deep learning techniques.

---

## Objectives

* To classify fabric surface defects using image classification techniques.
* To develop a **CNN-based deep learning model** for defect detection.
* To compare the performance of a traditional CNN model with a **MobileNetV2 transfer learning model**.
* To evaluate model performance using standard evaluation metrics.

---

## Dataset Information

### Dataset Name

**Fabric Surface Defect Dataset**

### Dataset Description

The dataset contains images of fabric surface defects categorized into different defect classes.

### Classes Used

* Hole
* Lines

### Image Size

**128 × 128 pixels**

### Dataset Source

Kaggle Dataset

**Dataset Link:** *(Paste your Kaggle dataset link here)*

---

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Scikit-learn
* Kaggle Notebook

---

## Project Workflow

1. Dataset Loading
2. Image Preprocessing
3. Image Resizing and Normalization
4. Train/Validation/Test Split
5. Data Augmentation
6. CNN Model Development
7. Model Training
8. Model Evaluation
9. Confusion Matrix Generation
10. Classification Report
11. Transfer Learning using MobileNetV2
12. Model Performance Comparison

---

## CNN Model Architecture

The CNN model includes:

* Convolutional Layers (Conv2D)
* Max Pooling Layers
* Flatten Layer
* Dense Fully Connected Layer
* Dropout Layer
* Softmax Output Layer

---

## Transfer Learning Model

This project uses **MobileNetV2** as a transfer learning model.

The pre-trained weights are used to improve classification performance and reduce training complexity, especially for smaller datasets.

---

## Evaluation Metrics

The following metrics were used to evaluate model performance:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Validation Loss

---

## Results

The project compares the performance of:

| Model       | Description                         |
| ----------- | ----------------------------------- |
| CNN         | Custom Convolutional Neural Network |
| MobileNetV2 | Transfer Learning Model             |

The comparison is based on accuracy and classification performance.

---

## Repository Structure

```text
project-folder/
│── notebook.ipynb
│── README.md
│── dataset_link.txt
│── output_images/
│    ├── accuracy_curve.png
│    ├── loss_curve.png
│    ├── confusion_matrix.png
│── results/
```

---

## How to Run the Project

1. Open the Kaggle Notebook or Jupyter Notebook.
2. Upload the dataset.
3. Install required libraries.
4. Run all notebook cells sequentially.
5. Train the CNN and MobileNetV2 models.
6. Evaluate model performance.
7. View generated graphs and classification results.

---

## Conclusion

This project demonstrates the use of **deep learning for automated fabric surface defect classification**. The comparison between CNN and MobileNetV2 helps identify the most efficient model for industrial defect detection and quality inspection.

---

## Author

**Jordan Jesudas**
Electronics Engineer | Machine Learning Enthusiast

