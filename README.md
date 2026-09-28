# 🧠 Basic Neural Network From Scratch

## 📌 Project Overview

This project implements a basic neural network from scratch using Python and NumPy for handwritten digit classification.

The objective is to understand the fundamental working of a neural network without relying on high-level machine learning frameworks for the model implementation.

The model is trained on the MNIST handwritten digit dataset and classifies images into digits from 0 to 9.

---

## 🎯 Objectives

The project demonstrates:

* Data preprocessing
* Neural network architecture
* Forward propagation
* ReLU activation
* Softmax activation
* Cross-entropy loss
* Backpropagation
* Gradient descent
* Mini-batch training
* Accuracy evaluation
* Result visualization

---

## 🛠️ Technologies Used

* Python
* NumPy
* Matplotlib
* Google Colab
* MNIST Dataset

---

## 🧠 Neural Network Architecture

The neural network consists of three layers:

```text
Input Layer
784 neurons
     ↓
Hidden Layer
128 neurons
     ↓
ReLU Activation
     ↓
Output Layer
10 neurons
     ↓
Softmax
     ↓
Digit Prediction (0-9)
```

### Input Layer

Each MNIST image is 28 × 28 pixels.

The image is flattened into:

```text
28 × 28 = 784
```

input features.

### Hidden Layer

The hidden layer contains 128 neurons and uses the ReLU activation function.

### Output Layer

The output layer contains 10 neurons representing the digits:

```text
0 1 2 3 4 5 6 7 8 9
```

Softmax converts the output values into probabilities.

---

## 🔄 Training Process

The model follows this process:

```text
Input Image
     ↓
Preprocessing
     ↓
Forward Propagation
     ↓
Prediction
     ↓
Cross-Entropy Loss
     ↓
Backpropagation
     ↓
Gradient Calculation
     ↓
Weight Update
     ↓
Next Training Batch
```

This process is repeated for multiple epochs.

---

## 📊 Training Configuration

| Parameter     |          Value |
| ------------- | -------------: |
| Input Size    |            784 |
| Hidden Layer  |            128 |
| Output Size   |             10 |
| Batch Size    |            128 |
| Epochs        |             10 |
| Learning Rate |           0.01 |
| Activation    | ReLU + Softmax |
| Loss          |  Cross-Entropy |

---

## 📈 Results

The model was trained for 10 epochs.

### Training Results

| Epoch |   Loss | Accuracy |
| ----: | -----: | -------: |
|     1 | 2.2173 |   57.16% |
|     2 | 1.4421 |   78.63% |
|     3 | 0.7870 |   83.81% |
|     4 | 0.5793 |   86.78% |
|     5 | 0.4881 |   88.23% |
|     6 | 0.4370 |   89.09% |
|     7 | 0.4045 |   89.75% |
|     8 | 0.3823 |   89.96% |
|     9 | 0.3657 |   90.24% |
|    10 | 0.3526 |   90.51% |

### Final Test Results

```text
Test Loss:     0.3315
Test Accuracy: 90.62%
Test Samples:  10,000
```

---

## 📷 Visualizations

The project includes visualizations for:

1. Sample MNIST images
2. Training loss
3. Training accuracy
4. Model predictions
5. Incorrect predictions

---

## 📁 Project Files

```text
AI-Intern-Week1/
│
├── Basic_Neural_Network_From_Scratch.ipynb
├── README.md
├── requirements.txt
│
└── screenshots/
    ├── dataset.png
    ├── loss_graph.png
    ├── accuracy_graph.png
    └── predictions.png
```

---

## ▶️ How to Run

### Option 1 — Google Colab

Open the notebook in Google Colab and run the cells sequentially.

### Option 2 — Local Python Environment

Install the required libraries:

```bash
pip install -r requirements.txt
```

Then open the Jupyter notebook:

```bash
jupyter notebook
```

Run:

```text
Basic_Neural_Network_From_Scratch.ipynb
```

---

## 📚 What I Learned

Through this project, I gained practical understanding of:

* How neural-network parameters are initialized
* How data moves through a neural network
* How ReLU and Softmax work
* How cross-entropy loss measures prediction error
* How backpropagation calculates gradients
* How gradient descent updates model parameters
* How mini-batch training works
* How to evaluate a model using test accuracy
* How to visualize training performance

---

## 👩‍💻 Project Type

**AI Internship — Week 1**

**Project:** Basic Neural Network From Scratch

**Framework:** NumPy

**Dataset:** MNIST

**Final Test Accuracy:** 90.62%
