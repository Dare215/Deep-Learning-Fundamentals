# Cats vs Dogs Deep Learning Classification

Deep learning computer vision project using **TensorFlow/Keras Convolutional Neural Networks (CNNs)** to classify **cats vs dogs images** through dataset preparation, CNN modeling, training, and evaluation.

---

## Project Overview

This project explores supervised deep learning image classification using the **Cats vs Dogs dataset**.

The assignment was completed in two stages:

- **Part 1:** Baseline Deep Learning Model
- **Part 2:** Advanced CNN Classification Pipeline

The project demonstrates:

- Data preprocessing
- TensorFlow dataset pipelines
- CNN architecture development
- Model training
- Validation monitoring
- Performance evaluation
- Accuracy visualization

---

## Repository Structure

```text
Cats-vs-Dogs-Deep-Learning-Classification/
│
├── notebooks/
│   ├── cats_dogs_part1_baseline.ipynb
│   └── cats_dogs_part2_advanced_cnn.ipynb
│
├── visuals/
│   ├── cnn_architecture.png
│   ├── data_pipeline_visualization.png
│   ├── dataset_samples.png
│   ├── model_evaluation.png
│   ├── training_results.png
│   ├── part1_accuracy_curve.png
│   └── part1_training_results.png
│
├── requirements.txt
└── README.md
```

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

---

## Dataset Preparation

Images were prepared using TensorFlow preprocessing workflows including:

- Image decoding
- Resizing
- Normalization
- Dataset batching
- Dataset shuffling
- Prefetch optimization
- Data augmentation

### Data Pipeline Visualization

![Data Pipeline](visuals/data_pipeline_visualization.png)

---

## Dataset Samples

Example training images used during preprocessing and validation.

![Dataset Samples](visuals/dataset_samples.png)

---

## CNN Architecture

The convolutional neural network architecture consisted of:

- Conv2D layers
- MaxPooling layers
- Flatten layer
- Dense hidden layer
- Output classification layer

### CNN Architecture

![CNN Architecture](visuals/cnn_architecture.png)

---

## Model Training Results

The model was trained using TensorFlow/Keras.

Training included:

- Validation monitoring
- Early stopping
- Model checkpointing
- Accuracy tracking
- Loss monitoring

### Training Results

![Training Results](visuals/training_results.png)

---

## Model Evaluation

The trained CNN was evaluated on a held-out test dataset to assess generalization performance.

Evaluation metrics included:

- Test Accuracy
- Validation Accuracy
- Loss
- Precision
- Recall
- AUC

### Model Evaluation

![Model Evaluation](visuals/model_evaluation.png)

---

## Baseline Results — Part 1

Part 1 established a baseline deep learning benchmark before implementing the advanced CNN workflow.

### Baseline Training Results

![Part 1 Training Results](visuals/part1_training_results.png)

### Accuracy Curve

Training and validation accuracy curves were used to assess learning behavior and detect overfitting patterns.

![Part 1 Accuracy Curve](visuals/part1_accuracy_curve.png)

---

## Key Learning Outcomes

This project demonstrates practical experience with:

✔ Deep Learning Fundamentals

✔ TensorFlow / Keras Workflows

✔ CNN Development

✔ Computer Vision Classification

✔ Dataset Pipelines

✔ Performance Evaluation

✔ Overfitting Detection

✔ Training Visualization

---

## Future Improvements

Potential future enhancements include:

- Transfer Learning (ResNet, EfficientNet, MobileNet)
- Hyperparameter Optimization
- Larger Training Dataset
- Advanced Data Augmentation
- Explainable AI Visualization (Grad-CAM)
- GPU-accelerated training

---

## Author

**Darious Brown**  
PhD — Artificial Intelligence & Machine Learning

Portfolio:  
https://dare215.github.io/DariousBrown-Portfolio/
