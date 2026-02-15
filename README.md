# Neural Network From Scratch (NumPy)

A simple implementation of a fully connected neural network built completely from scratch using **NumPy only** (no deep learning frameworks).
The model is trained to perform **multi-class classification** on a synthetic dataset and visualize the learned decision boundary.

---

## 📌 Features

* Forward propagation
* Backpropagation
* ReLU activation
* Softmax classifier
* Cross-entropy loss
* L2 Regularization
* Kaiming (He) weight initialization
* Gradient Descent optimization
* Decision boundary visualization

---

## 🧠 Network Architecture

Input → Hidden Layer → Output Layer

* Input layer: 2 features
* Hidden layer: 25 neurons (ReLU activation)
* Output layer: K neurons (Softmax)

[
X → (W1,b1) → ReLU → (W2,b2) → Softmax → Prediction
]

---

## 📂 Project Structure

```
.
├── neural_network.py     # Main neural network implementation
├── utils.py              # Dataset generation & plotting functions
├── README.md
└── .gitignore
```

---

## ⚙️ Requirements

Install dependencies:

```
pip install numpy matplotlib
```

---

## ▶️ How to Run

```
python neural_network.py
```

The script will:

1. Generate a synthetic dataset
2. Train the neural network
3. Print training loss
4. Display the decision boundary plot

---

## 📊 Example Output

During training:

```
At iteration 0 we have a cost of 1.09
At iteration 2500 we have a cost of 0.42
At iteration 5000 we have a cost of 0.18
At iteration 7500 we have a cost of 0.09
At iteration 10000 we have a cost of 0.05
```

A plot window will open showing classification regions learned by the model.

---

## 🧮 Loss Function

Cross-Entropy Loss with L2 Regularization:

[
J = -\frac{1}{m}\sum \log(p_{correct}) + \frac{\lambda}{2} (||W1||^2 + ||W2||^2)
]

---

## 📚 Learning Purpose

This project is designed to understand:

* How neural networks actually work internally
* How gradients are computed manually
* Why activation functions are required
* How softmax classification operates
* How decision boundaries are formed

---

## 🚀 Future Improvements

* Add multiple hidden layers
* Implement mini-batch gradient descent
* Add Adam optimizer
* Add different activation functions
* Load real datasets

---

## Author

Reimplemented for learning purposes based on the concept of building neural networks from scratch.
