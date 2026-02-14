# COM6104-Week5-NeuralNetworks
COM6104 Week 5 lab — Neural networks with TensorFlow and PyTorch on the mushroom dataset, including preprocessing, parameter analysis, and accuracy improvements
# Neural Networks Lab – Week 5

## 📌 Overview
This project explores the use of **TensorFlow** and **PyTorch** to build and compare neural networks for binary classification on the mushroom dataset.  
It demonstrates preprocessing, parameter counting, and accuracy improvements using regularization techniques.

> 📝 **Note**: This is the **fifth lab assignment** for **COM6104 – Topics in Data Science and Artificial Intelligence**.

---

## 🎯 Motivation
Neural networks are powerful tools for classification tasks.  
This lab highlights:
- How to preprocess categorical data with **OrdinalEncoder** and **StandardScaler**.  
- How to implement fully connected networks in both **TensorFlow** and **PyTorch**.  
- How to analyze parameter counts and understand model complexity.  
- How to improve accuracy with **BatchNorm** and **Dropout**.

---

## ⚙️ Exercises Implemented
All exercises are contained in **one notebook**: `p253572_lab5.ipynb`.

- **Exercise 1: TensorFlow Neural Network**  
  - Sequential model with three hidden layers (ReLU) and one output layer (Sigmoid).  
  - Parameter count: 1,116.  

- **Exercise 2: PyTorch Neural Network**  
  - Custom `Net` class with three hidden layers and sigmoid output.  
  - Parameter count: 1,116.  

- **Exercise 3: Improved PyTorch Model**  
  - Adds **BatchNorm** and **Dropout (30%)** to reduce overfitting.  
  - Parameter count: 1,226.  

---

## 📊 Sample Outputs
| Exercise   | Example | Output |
|------------|---------|--------|
| TensorFlow | `model.summary()` | Shows 1,116 parameters across 4 layers. |
| PyTorch    | `print(model)` | Displays architecture and parameter count. |
| Improved   | `print(model)` | Includes BatchNorm + Dropout layers, 1,226 parameters. |

---

## 🚀 How to Run
Install dependencies:
```bash
pip install -r requirements.txt
