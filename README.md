## Applied Deep Learning with TensorFlow



### Project Overview

This repository serves as a centralized hub for my machine learning projects and tasks completed at LAB University of Applied Sciences. The focus of this work is the numerical foundation of deep learning, ranging from basic tensor manipulations to complex image classification and regression tasks.
The core goal is to build high-performance neural networks while balancing model efficiency (parameter count) against classification accuracy.

------------------------------
### Key Features

* Numerical Foundations: Implementation of scalar, vector, matrix, and higher-dimensional tensor operations.
* Three-Step Keras Workflow: Standardized Create → Compile → Fit mental model applied across all tasks.
* Optimization-to-Accuracy Scoring: A custom logic to evaluate model performance vs. model weight (Parameter count).
* Multi-Domain Tasks:
* Regression: Predicting continuous linear values.
   * Binary Classification: Object detection (e.g., Pizza vs. Steak).
   * Multiclass Classification: Categorizing fashion items and CIFAR-10 objects.
* Advanced Techniques: Implementation of CNNs, Data Augmentation, and Transfer Learning.

------------------------------
### Tech Stack

* Framework: TensorFlow / Keras
* Numerical Processing: NumPy
* Visualization: Matplotlib
* Data Handling: Scikit-learn (splits and dataset generation)
* Dataset Sources: Fashion-MNIST, CIFAR-10, and custom synthetic data.

------------------------------
### Project Structure

├── ML_Code_Base/             # Core .ipynb notebooks for all tasks

├── Data/                     # Image datasets (Pizza, Steak, Fashion)

├── Models/                   # Exported .keras files

├── Evaluations/              # Accuracy vs. Parameter scoring logic

├── README.md                 # Project documentation

├── .gitignore                # Python & Jupyter exclusion rules

└── LICENSE                   # MIT Open Source License

------------------------------
### Highlighted Tasks & Assignments
### 1. Model Efficiency Challenge (Optimization vs. Accuracy)
A custom scoring function was developed to penalize models that are "too heavy" while rewarding accuracy.

* The Reward Logic:
* $1-5,000$ correct: $100€$ each
   * $5,001-6,000$ correct: $200€$ each
   * $>6,000$ correct: $1,000€$ each
* The Penalty: Total trainable parameter count is subtracted from the reward.
* Goal: Achieve the highest Net Score.

### 2. Regression Analysis
Implemented a neural network to learn the linear relationship $y = x + 10$.

* Metric: Mean Absolute Error (MAE).
* Visualization: Plotting ground truth vs. model predictions to identify bias.

### 3. Image Classification (CNNs)
Transitioned from Dense networks to Convolutional Neural Networks to preserve spatial structures.

* Tasks: Binary classification of food items and multiclass classification of Fashion-MNIST.
* Tools: Conv2D, MaxPool2D, and Flatten layers.

------------------------------
### Security & Best Practices

* Secret Protection: Active to prevent the accidental commit of API keys or Lab credentials.
* Data Preprocessing: All image data is normalized to $[0, 1]$ to stabilize gradients and accelerate training.

------------------------------
### Roadmap

* Complete Tensor foundation tasks.
* Implement initial Regression and Binary models.
* Optimize CNN architectures to maximize "Net Score."
* Implement Transfer Learning using EfficientNet for complex image tasks.

------------------------------
### Contributing
This is an academic repository. However, feedback on model optimization and hyperparameter tuning is always welcome.

   1. Fork the repo.
   2. Create your feature branch.
   3. Submit a Pull Request.

------------------------------
### License
This project is licensed under the MIT License.

------------------------------
### Contact
Nikita
Email: Nikita.K.C@student.lab.fi
GitHub: nikitakc12

------------------------------
